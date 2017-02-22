# @package exadra37-docker/test
# @link    https://gitlab.com/u/exadra37-docker/test
# @link    https://hub.docker.com/r/exadra37/test
# @since   2016/10/30
# @license MIT
# @author  Exadra37(Paulo Silva) <exadra37ingmailpointcom>
#
# Social Links:
# @link    Author:   https://exadra37.com
# @link    Gitlab:   https://gitlab.com/Exadra37
# @link    Github:   https://github.com/Exadra37
# @link    Docker:   https://hub.docker.com/u/exadra37/
# @link    Linkedin: https://uk.linkedin.com/in/exadra37
# @link    Twitter:  https://twitter.com/Exadra37

FROM ubuntu:latest
MAINTAINER Exadra37(Paulo Silva) <exadra37ingmailpointcom>
LABEL version="0.0.1"
LABEL description="Latest vanilla Ubuntu version."
LABEL com.exadra37.release-date="2016-10-30"
LABEL com.exadra37.environment="development"


RUN apt-get update && apt-get -y install zsh curl git

# Enhance ZSH shell with the wonderful Oh My ZSH
RUN bash -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# Set ZSH as the default shell
RUN chsh -s /usr/bin/zsh

ENTRYPOINT ["zsh"]
