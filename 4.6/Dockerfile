FROM node:4.6

# Install strong-build/strong-pm/strong-deploy
RUN useradd -ms /bin/bash strong-base \
    && chown -R strong-base:strong-base /usr/local \
    && su strong-base -c "npm install -g strong-build strong-pm strong-deploy && npm cache clean"