# git-resolver-test
This repository is used to test the functionality of git resolvers.
## Specifying a remote pipeline or task
To specify a remote pipeline or task from a Git repository, use the following reference format under **pipelineRef** or **taskRef**:
```  
  resolver: git
  params:
  - name: url
    value: <git-repo-url>
  - name: revision
    value: <branch-name>
  - name: pathInRepo
    value: <path-in-repo>
