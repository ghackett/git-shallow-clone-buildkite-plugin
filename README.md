# Git Shallow Clone Buildkite Plugin

plugin to manage git checkouts in a very specific way
 - goal is to export GIT_DEST_SHA as meta-data so that we can run affected checks
 - secondary goal is for checkouts to be as fast as possible
 - assumes that the all PRs are merged with squash-commits