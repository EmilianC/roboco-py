# 0.5.0 Beta (February 23rd, 2024)

- Replaced print() usages with the more structured logging module
- Minor cleanup

# 0.4.0 Beta (August 16th, 2023)

- Fixed stdout pipe emitting extra newlines
- Header and summary are now only shown in verbose mode
- Minor consistency fixes and cleanup

# 0.3.0 Alpha (August 16th, 2023)

- Fixed destination asserts if the folder didn't exist yet
- All operations now use multithreaded mode
- Added '/im' flag to ensure existing files are updated when mirroring
- Robocopy's return code is now always printed
