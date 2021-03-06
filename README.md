# boxupp  ![Travis status](https://api.travis-ci.org/BoxUpp/boxupp.svg)
<b> Browser based interface to manage your Vagrant environments </b>

Boxupp is built over Vagrant and exposes all the functionalities offered by Vagrant and much more inside your web-browser.

Vagrant is an awesome tool to manage the development environments and we want to enhance the experience even further.

### Features:<hr>

#### 1) Inbuilt Vagrant Intelligence
You do not need to learn Vagrant syntax. Boxupp knows what vagrant commands to run to bring your dashboard box 
states in sync with the real infrastructure at the backend. Forget infrastructure management issues and focus on coding instead.

#### 2) Puppet Forge Integration
Boxupp supports around 2.8k+ modules from Puppet Forge. You can search and download a required module from the Puppet Forge 
repository and link it with any of the boxes defined in your Boxupp Dashboard.

#### 3) Manage multiple workspaces in your browser
Super easy to create workspaces using providers viz. Docker and VirtualBox. Navigate effortlessly from one workspace to the 
other. Define boxes, modules, scripts within your workspaces and much more.

#### 4) Github integration
Share your infrastructure as code on Github from within your Boxupp's control panel. This will help you collaborate, get feedback, 
get contributions from your team members or peer groups which will help in seamless development across teams.

### Usage Instructions <hr>

1) Clone the repository on your local machine

    git clone https://www.github.com/boxupp/boxupp.git
2) Change to the cloned directory

    cd boxupp
3) Package in Maven

    mvn package
4) Run the Boxupp program

    cd target\boxuppzipdir\bin
    startup.bat OR ./startup.sh
    
5) Start boxupp in your browser at 

    http://localhost:<<PORT_NUMBER configured in config.xml>> (By Default 8585)





