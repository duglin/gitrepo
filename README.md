# gitrepo

A simple tool for creating org repositories. It initializes the repo(s) with an Apache 2.0 license.

## Usage

`gitrepo -t TOKEN [OPTIONS] ORG/NAME,...`

Options:

- `t (string)` - User API token (required)
- `a (string)` - Comma separated users to add to the repo(s)
- `o (bool)` - Add users to the organization as members in addition to adding them to the repo(s)
- `r (string)` - Comma separated users to remove from the repo(s)
- `d (string)` - Description of the repo(s)