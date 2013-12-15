brutasse.github.io
==================

Based on the source code for http://twitter.github.io/, rewritten in
AngularJS.

Usage
-----

Fork and rename to `<username>.github.io`.

Edit `index.html` and set your parameters in the opening `<body>` block:

```
<body data-username="brutasse" data-additional="feedhq/feedhq" ng-controller…>
```

Set `data-username` to your GitHub username. If you want additional repos in
other accounts/orgs to appear on your dashboard, use `data-additional`. This
is a comma-separated list of `<organization>/<repo>` values.

Commit, push and visit `<username>.github.io` to see the results.

LICENSE
-------

Copyright 2012 Twitter, Inc.

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
