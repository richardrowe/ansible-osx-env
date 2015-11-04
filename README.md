# ansible-osx-env
An Ansible playbook for provisioning a local OS X system.

# Prerequisites

1. Install Xcode
  ```bash
  $ xcode-select --install
  ```
  (select the **Get Xcode** option and install the full suite)

2. Agree to the xcode license
  ```bash
  $ sudo xcrun cc
  ```

3. Install Homebrew
  ```bash
  $ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  $ brew doctor
  ```

4. Install Ansible
  ```bash
  $ brew install ansible
  ```

5. Clone this repo locally
  ```bash
  $ git clone https://github.com/richardrowe/ansible-osx-env.git
  ```

OR

Run the `bootstrap.sh` script:

```$ bootstrap.sh```