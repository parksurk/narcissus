0. Install OS : Ubuntu 16.04

1. Install NVM("Node.js version manager") and Node.js v7.6.0
    <pre><code>
    sudo apt-get update
    sudo apt-get install build-essential libssl-dev
    curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh
    bash install_nvm.sh
    source ~/.profile
    nvm ls-remote
    nvm install 7.6.0
    nvm use 7.6.0
    node -v
    nvm alias default 7.6.0
    nvm use default
    </code></pre>
    
    ref : https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-16-04
    
2. Clone the repository and check out the master branch
    <pre><code>
    git clone https://github.com/MichMich/MagicMirror
    </code></pre>

3. Enter the repository
    <pre><code></code></pre>
    cd ~/MagicMirror
    </code></pre>

4. Install and run the app
    <pre><code></code></pre>
    npm install && npm start
    </code></pre>
