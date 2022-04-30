# Stale Bots

We use a stale bot to mark issues as inactive to make sure our projects keep up with their current goals and objectives, and to clear up issues that nobody no longer cares about.

However, as a result, some issues that do need attention could end up getting marked as stale and then closed, which nobody cares about until one day someone finds that issue and opens another issue.

## Filter rules

All issues will be marked as stale after fourteen days of detected inactivity. After that, if the issue has had a further seven days of inactivity, it is closed.

## Issues needs Attention

For critical issues, maintainers are advised to add the `keep alive` label to such issues.

For our configuration, the Stale Bot will ignore any issues with `keep alive` label even if it stays there for years, but maintainer **should** remove once it is no longer neccessary to keep the issue open.

## Pull Requests

Stale bots should ignore pull requests.
