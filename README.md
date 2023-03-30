# gitest1
23.3.24 create jenkins project
        git push trigger jenkins build test

23.3.27 git push trigger jenkins build test 
        jenkins project setting > build trigger github hook trigger gor GITMcm polling
        install jenkins plugin GITHUB Intergration
        change jenkins configure > add hook url
        
23.3.28 view github/settings/hooks
        pipeline script use hello world example
        create new pipeline and build

23.3.29 add credential(github access token) > delete cicdadm credential
        create new pipeline
        edit pipeline github project path
        pipeline build now
        edit pipeline script
            git url: 'github https url', branch:'branchname'
        first build
        delete hkh961217
        auto create jenkins user hkh961217
        edit pipeline script 'stages gitpush'
        jenkins build error 403
        download sample.war in jenkins (/var/lib/jenkins/workspace)

23.3.30 ahfmrpTek
        pipeline script scm
