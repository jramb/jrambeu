# Check locally

- `git clone https://github.com/jramb/jrambeu.git`
- `cd jrambeu`
- `git submodule update --init --recursive`


- `hugo server  -w -D --bind 0.0.0.0 -b http://localhost:1313`
- To publish
  - `hugo`
  - `git add *`
  - `git commit -am "comment"`
  - `git push`
  - wait 5 minutes
