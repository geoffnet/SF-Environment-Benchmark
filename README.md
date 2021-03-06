# [SF-Environment-Benchmark](http://smoningi.github.io/SF-Environment-Benchmark/Prototype%20Visualization/)
Set of applications to visualize SF building energy consumption and greenhouse gas emissions.

The original goal of the SF Environment Benchmark project was to visualize building energy consumption and greenhouse gas emissions to encourage owners and building managers to make proper changes. In addition we would like to analyze the data available to see if we can predict what energy consumption or emissions will be like in the future. We've currently developed a prototype web application that visualizes the data in an interactive format. In addition, we'll be meeting with the SF Department of Environment, who are the stewards of the data, to see what their needs and requirements are. We can cater the project to their needs and requirements to make sure to solve problems at hand.


SF Environment Benchmark part of the Data Science Working Group at Code for San Francisco.

## Getting Started

[Fork this repo](https://help.github.com/articles/fork-a-repo/), then clone your repo locally
```
$ git clone <your-repo>
$ git remote add upstream <this-repo>
```
Launch a local server.  If you're on a Mac, you already have [SimpleHTTPServer](http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/) installed:  
```
$ cd path/to/local/clone
$ python -m SimpleHTTPServer
```
You could also use [http-server](https://www.npmjs.com/package/http-server) if you wanted  
Create a feature branch:
```
$ git checkout -b <feature-branch>
```
Do some work:  
```
$ vim <some-files>
```
When you're ready, commit, [merge any upstream changes](https://help.github.com/articles/merging-an-upstream-repository-into-your-fork/), [deal with conflicts](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/), and push your branch ([aka, forking workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/forking-workflow))   
```
$ git commit -am 'my awesome feature'
$ git pull upstream master
  # solve conflicts
$ git push
```
[Create a Pull Request](https://help.github.com/articles/creating-a-pull-request/) from your pushed branch (compare branch) to this repo (base branch)   
...  
Profit!
