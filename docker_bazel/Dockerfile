FROM docker_git:latest
RUN add-apt-repository ppa:webupd8team/java && apt-get update && apt-get --assume-yes install oracle-java8-installer && wget https://github.com/bazelbuild/bazel/releases/download/0.2.2b/bazel-0.2.2b-installer-linux-x86_64.sh && chmod +x bazel-0.2.2b-installer-linux-x86_64.sh && ./bazel-0.2.2b-installer-linux-x86_64.sh --user
