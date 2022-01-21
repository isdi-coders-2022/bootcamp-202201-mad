#!/bin/sh
. "$(dirname "$0")/_/husky.sh"

while read line; do
    # Skip comments
    if [ "${line:0:1}" == "#" ]; then
        continue
    fi
    if [ ${#line} -ge 72 ] || [ ${#line} -le 10 ]; then
        echo -e "\033[0;31mThe length of the message has to be between 10 and 72 characters."
        exit 1
    fi
done < "${1}"

exit 0