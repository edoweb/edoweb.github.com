h1. Usage

To deploy artifacts to this repo use the tutorial at
http://cemerick.com/2010/08/24/hosting-maven-repos-on-github/

or

1. git clone https://github.com/edoweb/edoweb.github.com
2. 2. cd $EDOWEB2_HOME
3. mvn  mvn -DaltDeploymentRepository=snapshot-repo::default::file:///$MAVEN-REPO_HOME/snapshots clean deploy
4. cd $MAVEN-REPO_HOME
5. git add *
6. git commit -a
7. git push
