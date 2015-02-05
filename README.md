## pair-branch

A utility to create branches named following a convention of 'pair-github_id_1,github_id_2'

### Installation

  $ git clone https://github.com/Devbootcamp/pair-branch.git
  
  $ cd pair-branch
  
  $ ./install # will install to /usr/local/bin

**Note** This utility is dependent on having [set-git-user](../../../set-git-user) utility installed for setting up the git config for pair work on your workstation. Please install that first.

#### The simplest use of this utility for pairing: 

  $ weare alycit mikelikesbikes  #this is from the set-git-user utility
  
  $ cd project_git_repo
  
  $ pair-branch
  
  Switched to a new branch 'pair-alycit,mikelikesbikes'
  
  Ran the following command for you: git checkout -b "pair-alycit,mikelikesbikes"

#### If you are working solo, this is the workflow:

  $ iam alycit  #this is from the set-git-user utility
  
  $ cd project_git_repo
  
  $ pair-branch
  
  Switched to a new branch 'pair-alycit'
  
  Ran the following command for you: git checkout -b "pair-alycit"
