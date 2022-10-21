# Daily_Problems

Welcome to GitHub Daily Problems repository. This repository consists of daily projects implemented as a GitHub module. Each day a new problem will be solved and stored in this repository as a submodule. This will allow the daily projects to be imported into a java IDE directly from the GitHub submodule.

The original repository was created by utilizing the GitHub website and clicking on the “New” button from the Repositories tab. Please note that you must have SSH enabled to use commands such as the ones listed here.

The first step is to create a repository through your IDE of the daily problem. This repository will act as the submodule.

The second step is to create a repository to host the submodules.

The third step is to add the submodules to the repository which will host the submodules.

The following command was used to clone the empty repository:

git clone git@github.com:yoophglup/Daily_Problems.git

Then the submodules were added by using the following commane:

git submodule add git@github.com:yoophglup/day1.git

Then the local repository was committed using:

git commit -m "Add GitHub submodule"

Once all the submodules were created the main repository was uploaded to GitHub using:

git push origin

Using this same method each day a new repository will be added to reflect each daily problem. Each problem will have a markdown readme.md added to explain the problem and solution presented.
