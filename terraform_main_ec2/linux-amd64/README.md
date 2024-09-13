Helm
Build Status Go Report Card GoDoc CII Best Practices

Helm is a tool for managing Charts. Charts are packages of pre-configured Kubernetes resources.

Use Helm to:

Find and use popular software packaged as Helm Charts to run in Kubernetes
Share your own applications as Helm Charts
Create reproducible builds of your Kubernetes applications
Intelligently manage your Kubernetes manifest files
Manage releases of Helm packages
Helm in a Handbasket
Helm is a tool that streamlines installing and managing Kubernetes applications. Think of it like apt/yum/homebrew for Kubernetes.

Helm renders your templates and communicates with the Kubernetes API
Helm runs on your laptop, CI/CD, or wherever you want it to run.
Charts are Helm packages that contain at least two things:
A description of the package (Chart.yaml)
One or more templates, which contain Kubernetes manifest files
Charts can be stored on disk, or fetched from remote chart repositories (like Debian or RedHat packages)
Install
Binary downloads of the Helm client can be found on the Releases page.

Unpack the helm binary and add it to your PATH and you are good to go!

If you want to use a package manager:

Homebrew users can use brew install helm.
Chocolatey users can use choco install kubernetes-helm.
Scoop users can use scoop install helm.
Snapcraft users can use snap install helm --classic
To rapidly get Helm up and running, start with the Quick Start Guide.

See the installation guide for more options, including installing pre-releases.

Docs
Get started with the Quick Start guide or plunge into the complete documentation

Roadmap
The Helm roadmap uses GitHub milestones to track the progress of the project.

Community, discussion, contribution, and support
You can reach the Helm community and developers via the following channels:

Kubernetes Slack:
#helm-users
#helm-dev
#charts
Mailing List:
Helm Mailing List
Developer Call: Thursdays at 9:30-10:00 Pacific (meeting details)
Contribution
If you're interested in contributing, please refer to the Contributing Guide before submitting a pull request.

Code of conduct
Participation in the Helm community is governed by the Code of Conduct.
