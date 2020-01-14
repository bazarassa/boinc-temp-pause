# boinc-temp-pause
Bash script for temporary stopping running BOINC tasks, if CPU temperature reaches user-defined threshold
# Usage
`boinc-temp-pause [INTEGER]`, where INTEGER is threshold value in degrees. If CPU temperature reaches value that's more or equal then your threshold, BOINC will stop its tasks for 5 minutes.
# Running
Run this script with`watch -n 300 -c /bin/bash $PATH_TO_SCRIPT [INTEGER]`
