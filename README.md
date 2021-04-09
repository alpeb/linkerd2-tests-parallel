Linkerd2 Parallel Integration Tests
====================================

This triggers each integration test in its own tmux pane, in parallel.
It sets a different (temporarily) kubeconfig location for each test
to avoid config file locking issues.
To be run in a tmux session, under linkerd2's repo root dir after having
built all the docker images (with bin/docker-build)

![screenshot]()
