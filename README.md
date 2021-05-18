    # npm audit report

    merge  <2.1.1
    Severity: high
    Prototype Pollution - https://npmjs.com/advisories/1666
    No fix available
    node_modules/merge
      exec-sh  <=0.3.1
      Depends on vulnerable versions of merge
      node_modules/exec-sh
        watch  >=0.14.0
        Depends on vulnerable versions of exec-sh
        node_modules/watch
          @vue/cli-ui  *
          Depends on vulnerable versions of watch
          node_modules/@vue/cli-ui
            @vue/cli  *
            Depends on vulnerable versions of @vue/cli-ui
            node_modules/@vue/cli

    5 high severity vulnerabilities

    Some issues need review, and may require choosing
    a different dependency.
