#!/bin/sh
. "$(dirname "$0")/_/husky.sh"

local_branch_name="$(git rev-parse --abbrev-ref HEAD)"

valid_branch_regex='^((hotfix|bugfix|feature)\/[a-zA-Z0-9\-]+)$'

message="Please check your branch name."

if [[ ! $local_branch_name =~ $valid_branch_regex ]]; then
    echo -e "\033[0;31m$message"
    exit 1
fi

exit 0
