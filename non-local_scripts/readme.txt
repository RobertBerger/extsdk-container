Running from: /usr/share/jenkins/jenkins.war
webroot: EnvVars.masterEnvVars.get("JENKINS_HOME")
2020-03-22 13:00:19.296+0000 [id=1]     INFO    org.eclipse.jetty.util.log.Log#initialized: Logging initialized @297ms to org.eclipse.jetty.util.log.JavaUtilLog
2020-03-22 13:00:19.386+0000 [id=1]     INFO    winstone.Logger#logInternal: Beginning extraction from war file
2020-03-22 13:00:20.934+0000 [id=1]     WARNING o.e.j.s.handler.ContextHandler#setContextPath: Empty contextPath
2020-03-22 13:00:20.980+0000 [id=1]     INFO    org.eclipse.jetty.server.Server#doStart: jetty-9.4.z-SNAPSHOT; built: 2019-05-02T00:04:53.875Z; git: e1bc35120a6617ee3df05229
4e433f3a25ce7097; jvm 1.8.0_242-b08
2020-03-22 13:00:21.216+0000 [id=1]     INFO    o.e.j.w.StandardDescriptorProcessor#visitServlet: NO JSP Support for /, did not find org.eclipse.jetty.jsp.JettyJspServlet
2020-03-22 13:00:21.269+0000 [id=1]     INFO    o.e.j.s.s.DefaultSessionIdManager#doStart: DefaultSessionIdManager workerName=node0
2020-03-22 13:00:21.269+0000 [id=1]     INFO    o.e.j.s.s.DefaultSessionIdManager#doStart: No SessionScavenger set, using defaults
2020-03-22 13:00:21.273+0000 [id=1]     INFO    o.e.j.server.session.HouseKeeper#startScavenging: node0 Scavenging every 660000ms
2020-03-22 13:00:21.583+0000 [id=1]     INFO    hudson.WebAppMain#contextInitialized: Jenkins home directory: /var/jenkins_home found at: EnvVars.masterEnvVars.get("JENKINS_
HOME")
2020-03-22 13:00:21.677+0000 [id=1]     INFO    o.e.j.s.handler.ContextHandler#doStart: Started w.@26be6ca7{Jenkins v2.204.5,/,file:///var/jenkins_home/war/,AVAILABLE}{/var/
jenkins_home/war}
2020-03-22 13:00:21.689+0000 [id=1]     INFO    o.e.j.server.AbstractConnector#doStart: Started ServerConnector@19932c16{HTTP/1.1,[http/1.1]}{0.0.0.0:8080}
2020-03-22 13:00:21.689+0000 [id=1]     INFO    org.eclipse.jetty.server.Server#doStart: Started @2691ms
2020-03-22 13:00:21.690+0000 [id=22]    INFO    winstone.Logger#logInternal: Winstone Servlet Engine v4.0 running: controlPort=disabled
2020-03-22 13:00:22.787+0000 [id=29]    INFO    jenkins.InitReactorRunner$1#onAttained: Started initialization
2020-03-22 13:00:22.809+0000 [id=38]    INFO    jenkins.InitReactorRunner$1#onAttained: Listed all plugins
2020-03-22 13:00:23.875+0000 [id=35]    INFO    jenkins.InitReactorRunner$1#onAttained: Prepared all plugins
2020-03-22 13:00:23.880+0000 [id=42]    INFO    jenkins.InitReactorRunner$1#onAttained: Started all plugins
2020-03-22 13:00:23.887+0000 [id=36]    INFO    jenkins.InitReactorRunner$1#onAttained: Augmented all extensions
2020-03-22 13:00:24.345+0000 [id=36]    INFO    jenkins.InitReactorRunner$1#onAttained: Loaded all jobs
2020-03-22 13:00:24.363+0000 [id=55]    INFO    hudson.model.AsyncPeriodicWork#lambda$doRun$0: Started Download metadata
2020-03-22 13:00:24.376+0000 [id=55]    INFO    hudson.util.Retrier#start: Attempt #1 to do the action check updates server
2020-03-22 13:00:25.132+0000 [id=40]    INFO    o.s.c.s.AbstractApplicationContext#prepareRefresh: Refreshing org.springframework.web.context.support.StaticWebApplicationContext@266ebf71: display name [Root WebApplicationContext]; startup date [Sun Mar 22 13:00:25 UTC 2020]; root of context hierarchy
2020-03-22 13:00:25.132+0000 [id=40]    INFO    o.s.c.s.AbstractApplicationContext#obtainFreshBeanFactory: Bean factory for application context [org.springframework.web.context.support.StaticWebApplicationContext@266ebf71]: org.springframework.beans.factory.support.DefaultListableBeanFactory@5733e36c
2020-03-22 13:00:25.143+0000 [id=40]    INFO    o.s.b.f.s.DefaultListableBeanFactory#preInstantiateSingletons: Pre-instantiating singletons in org.springframework.beans.factory.support.DefaultListableBeanFactory@5733e36c: defining beans [authenticationManager]; root of factory hierarchy
2020-03-22 13:00:25.346+0000 [id=40]    INFO    o.s.c.s.AbstractApplicationContext#prepareRefresh: Refreshing org.springframework.web.context.support.StaticWebApplicationContext@49f50acd: display name [Root WebApplicationContext]; startup date [Sun Mar 22 13:00:25 UTC 2020]; root of context hierarchy
2020-03-22 13:00:25.346+0000 [id=40]    INFO    o.s.c.s.AbstractApplicationContext#obtainFreshBeanFactory: Bean factory for application context [org.springframework.web.context.support.StaticWebApplicationContext@49f50acd]: org.springframework.beans.factory.support.DefaultListableBeanFactory@5137744d
2020-03-22 13:00:25.347+0000 [id=40]    INFO    o.s.b.f.s.DefaultListableBeanFactory#preInstantiateSingletons: Pre-instantiating singletons in org.springframework.beans.factory.support.DefaultListableBeanFactory@5137744d: defining beans [filter,legacy]; root of factory hierarchy
2020-03-22 13:00:25.658+0000 [id=40]    INFO    jenkins.install.SetupWizard#init:

*************************************************************
*************************************************************
*************************************************************

Jenkins initial setup is required. An admin user has been created and a password generated.
Please use the following password to proceed to installation:

8eddd7f90dde439da0dec0a4f7ae1a1a

This may also be found at: /var/jenkins_home/secrets/initialAdminPassword

*************************************************************
*************************************************************
*************************************************************

2020-03-22 13:00:29.844+0000 [id=55]    INFO    hudson.model.UpdateSite#updateData: Obtained the latest update center data file for UpdateSource default
2020-03-22 13:00:30.356+0000 [id=55]    INFO    h.m.DownloadService$Downloadable#load: Obtained the updated data file for hudson.tasks.Maven.MavenInstaller
2020-03-22 13:00:30.358+0000 [id=55]    INFO    hudson.util.Retrier#start: Performed the action check updates server successfully at the attempt #1
2020-03-22 13:00:30.362+0000 [id=55]    INFO    hudson.model.AsyncPeriodicWork#lambda$doRun$0: Finished Download metadata. 5,994 ms
2020-03-22 13:00:32.796+0000 [id=40]    INFO    hudson.model.UpdateSite#updateData: Obtained the latest update center data file for UpdateSource default
2020-03-22 13:00:32.948+0000 [id=40]    INFO    jenkins.InitReactorRunner$1#onAttained: Completed initialization
2020-03-22 13:00:32.958+0000 [id=21]    INFO    hudson.WebAppMain$3#run: Jenkins is fully up and running

------

http://192.168.42.1:8080

------

Unlock Jenkins
  copy/paste password from above

------

Customize Jenkins
  Install suggested plugins

------

Create First Admin User
     robert.berger
     rber@jenkins
     rber.jenkins@reliableembeddedsystems.com

------

Manage Jenkins > Manage Plugins > Available
    Cloudbees Docker Custom Build Environment
    Install without restart

------


Cloudbees Docker Custom Build Environment:
    *) seems to work to build docker containers 
    *) possibly to upload to docker.io (did not test)

------

build:
  execute shell

HERE=$(pwd)
#pwd
#ls
cd ${HERE}/local_scripts
#ls
./docker_build-only.sh ubuntu-16.04
cd ${HERE}

=====


==== fresh start? =====






