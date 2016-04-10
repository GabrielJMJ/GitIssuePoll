GitIssuePoll
============
Create simple polls for GitHub issues.

## Usage
### Parameters
* ```issue```: The issue -> :user/:repo/issues/:issue_id
* ```valid_votes``` (optional): Valid votes content
* ```ignore``` (optional): Comments IDs that must be ignored

### Example
```
http://gabrieljmj.github.io/GitIssuePoll/?ignore={:comment_id1,...}&issue={:user/:repo/issues/:id}
```
