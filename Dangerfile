# Warn when there are fixup/squash commits in the PR
if git.commits.any? { |c| c.message.include?('fixup!') || c.message.include?('squash!') }
 fail('There are some fixup/squash commits that needs to be applied before merge.')
end

# Check links
require 'json'
results = File.read 'ab-results-README.md-markdown-table.json'
j = JSON.parse results
if j['error']==true
  fail j['title']
  markdown j['message']
end
