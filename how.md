3.Trigger your first build with a git push

Once the GitHub hook is set up, push your commit that adds .travis.yml to your repository. That should add a build into one of the queues on Travis CI and your build will start as soon as one worker for your language is available.

To start a build, perform one of the following:

Commit and push something to your repository
Go to your repository's settings page, click on "Webhooks & Services" on the left menu, choose "Travis CI" in the "Services", and use the "Test service" button.
