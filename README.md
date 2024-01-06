# -GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /repos/OWNER/REPO/hooks
[
  {
    "type": "Repository",
    "id": 12345678,
    "name": "web",
    "active": true,
    "events": [
      "push",
      "pull_request"
    ],
    "config": {
      "content_type": "json",
      "insecure_ssl": "0",
      "url": "https://example.com/webhook"
    },
    "updated_at": "2019-06-03T00:57:16Z",
    "created_at": "2019-06-03T00:57:16Z",
    "url": "https://api.github.com/repos/octocat/Hello-World/hooks/12345678",
    "test_url": "https://api.github.com/repos/octocat/Hello-World/hooks/12345678/test",
    "ping_url": "https://api.github.com/repos/octocat/Hello-World/hooks/12345678/pings",
    "deliveries_url": "https://api.github.com/repos/octocat/Hello-World/hooks/12345678/deliveries",
    "last_response": {
      "code": null,
      "status": "unused",
      "message": null
    }
  }
]
