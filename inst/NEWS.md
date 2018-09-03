
# devel

* `gh_username()` caches the result, separately for each email address.

* `gh_username()` uses the `GITHUB_USERNAME` environment variable, if it
  it is set (#6, @maelle)
  
* On Windows, `gh_fullname` and `gh_email_address` try finding the global git configuration in `Sys.getenv("USERPROFILE")` if it doesn't find it in `Sys.getenv("HOME")` (#7, @maelle)

# 1.1.2

Maintainence release, no user visible changes

# 1.1.1

Maintainence release, no user visible changes

# 1.1.0

* Fallbacks, instead of errors, #2

# 1.0.0

First release
