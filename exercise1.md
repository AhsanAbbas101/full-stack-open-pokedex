For C programming language, some of the tools available for linting are <a href="https://clang.llvm.org/docs/ClangFormat.html">ClangFormat</a>, <a href="https://clang.llvm.org/extra/clang-tidy/">Clang-Tidy</a> and <a href="https://github.com/cpplint/cpplint">cpplint</a>. For testing, <a href="https://google.github.io/googletest/">GoogleTest</a>, <a href="https://github.com/ThrowTheSwitch/Unity">Unity</a> and <a href="https://www.boost.org/doc/libs/1_82_0/libs/test/doc/html/index.html">Boost.Test</a> are available. <a href="https://cmake.org/">CMake</a>, <a href="https://mesonbuild.com/">Meson</a> and <a href="https://ninja-build.org/">Ninja</a> tools are available for building the projects.

Some of the alternatives for setting up CI are <a href="https://circleci.com/">CircleCI</a>, <a href="https://www.jetbrains.com/teamcity/">TeamCity</a>, <a href="https://www.travis-ci.com/">TravisCI</a> and <a href="https://www.cloudbees.com/products/codeship">CodeShip</a>. Cloud providers such as AWS, Azure and Google Cloud also provide platforms for CI.  

The information required to make a decision about environment of CI setup is the team's needs, capabilities and priorities. Some of the questions to consider are: 

- Does the team have time, resources and competence to setup CI in a self-hosted environment?
- Can the team spare resources for managing the self-hosted environment?
- Does the organisation's regulations restrict using cloud-based environment?
- Does the team have security concerns for CI setup in cloud-based environment?
- Does the project have special requirements for building and testing?

For a given small team of 6 people in active deveploment of the application to be released soon,  the cloud-based environment for CI setup seems viable. The team has less time and resource to invest in setting up and managing CI in a self-hosted environment. Using a cloud-based environment will enable the team to focus on the deveploment itself, accelerate its deveploment and provide scalability. 