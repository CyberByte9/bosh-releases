# bosh-releases

This release is a modified version of the bosh-release v263.4.0.
This version fixes the SSRF Cloud Controller vulnerability which exposes credentials for underlying Cloud Infrastructure that would allow a malicious space developer to take over the entire infrastructure.

"<p id="explanation">You're seeing this error because you have
enabled the <code>show_exceptions</code> setting.</p>"

This release implements the fix in https://bosh.io/releases/github.com/cloudfoundry/bosh?version=263.4.0
