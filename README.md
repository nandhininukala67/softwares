FAILURE: Build failed with an exception.

* Where:
Build file 'F:\rtsp-switch-main\build.gradle' line: 87

* What went wrong:
A problem occurred configuring project ':modules:icici-rtsp'.
> Could not resolve all dependencies for configuration ':modules:icici-rtsp:runtime'.
   > A problem occurred configuring project ':modules:jpts'.
      > Could not resolve all files for configuration ':modules:jpts:runtime'.
         > Could not resolve org.jpos.ee:jposee-core:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-core:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-core:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-core:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-core:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-core/2.2.7/jposee-core-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-eeuser:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-eeuser:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-eeuser:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-eeuser:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-eeuser:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-eeuser/2.2.7/jposee-eeuser-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-visitor:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-visitor:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-visitor:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-visitor:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-visitor:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-visitor/2.2.7/jposee-visitor-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-quartz:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-quartz:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-quartz:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-quartz:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-quartz:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-quartz/2.2.7/jposee-quartz-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-eerest:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-eerest:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-eerest:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-eerest:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-eerest:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-eerest/2.2.7/jposee-eerest-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-resultcode:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-resultcode:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-resultcode:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-resultcode:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-resultcode:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-resultcode/2.2.7/jposee-resultcode-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-txn:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-txn:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-txn:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-txn:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-txn:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-txn/2.2.7/jposee-txn-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-db-mysql:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-db-mysql:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-db-mysql:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-db-mysql:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-db-mysql:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-db-mysql/2.2.7/jposee-db-mysql-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-logback:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-logback:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-logback:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-logback:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-logback:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-logback/2.2.7/jposee-logback-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-syslog:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-syslog:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-syslog:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-syslog:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-syslog:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-syslog/2.2.7/jposee-syslog-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-sysconfig:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-sysconfig:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-sysconfig:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-sysconfig:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-sysconfig:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-sysconfig/2.2.7/jposee-sysconfig-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-mail:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-mail:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-mail:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-mail:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-mail:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-mail/2.2.7/jposee-mail-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
         > Could not resolve org.jpos.ee:jposee-saf:2.2.7.
           Required by:
               project :modules:jpts
            > Could not resolve org.jpos.ee:jposee-saf:2.2.7.
               > Could not get resource 'https://jpos.org/maven/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                  > Could not GET 'https://jpos.org/maven/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target
            > Could not resolve org.jpos.ee:jposee-saf:2.2.7.
               > Could not get resource 'http://download.oracle.com/maven/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                  > Could not GET 'http://download.oracle.com/maven/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-saf:2.2.7.
               > Could not get resource 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                  > Could not GET 'http://jline.sourceforge.net/m2repo/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'. Received status code 403 from server: Forbidden
            > Could not resolve org.jpos.ee:jposee-saf:2.2.7.
               > Could not get resource 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                  > Could not GET 'https://repository.jboss.org/nexus/content/repositories/releases/org/jpos/ee/jposee-saf/2.2.7/jposee-saf-2.2.7.pom'.
                     > sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.
Use '--warning-mode all' to show the individual deprecation warnings.
See https://docs.gradle.org/6.7.1/userguide/command_line_interface.html#sec:command_line_warnings
