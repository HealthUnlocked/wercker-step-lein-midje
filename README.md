# lein-midje

Executes `lein midje` command for testing Clojure projects on Wercker.

This requires that [lein-midje](https://github.com/marick/lein-midje) is listed
in your `project.clj` either as a top-level `:plugins` or inside your dev profile
(`:plugins` section).

You also need to ensure you are using a box with the correct JDK installed and
set as default.
