# Git auto push with auto code formatter.

> This script are using laravel/pint for formating code. You don't need  to install laravel/pint. This script automatically install laravel/pint if it's not installed in your composer package .
### How to use it
> Put git.sh in your project folder. Then make it executable by using this command.

    chmod +x git.sh

> Then use command to run

    sh git.sh --comment "first push" --branch "main"
> Or

    ./git.sh --comment "first push" --branch "main"

here,
--comment is what you want to commit before push.
--branch is which branch you want to update.
