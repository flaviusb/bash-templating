# bash-templating
A preprocessor that interpolates {{}} with the results of running what is inside there in bash.

## Usage

Run `btp units.🍍🍕.{}` in the project directory of your desktop publishing project, and it will generate a `units.🍍🍕` file for you by running all of the bash code in the template and splicing the results back in.

The code will be run from where ever you are invoking `btp` from.
