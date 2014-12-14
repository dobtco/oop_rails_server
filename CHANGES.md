# `oop_rails_server` Releases

## 0.0.5, 14 December 2014

* Added `json` as a dependency, since, under Ruby 1.8.7, it is not necessarily installed otherwise.
* `stderr` is now captured to the output file of the Rails server, as well as `stdout`.

## 0.0.4, 13 December 2014

* Better error messages in certain circumstances.
* Expose a `#run_command_in_rails_root!` method to allow executing arbitrary Rails-related commands in the
  server's root.