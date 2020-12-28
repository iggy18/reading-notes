# django best practice

- store sensitive passwords and keys in a settings_local.py file that is ignored by the VCS.

- environment variables. hide your sensitive data in a seperate file that is ignored by VCS.

- 12 Factors is a collection of recommendations on how to build distributed web-apps that will be easy to deploy and scale in the Cloud.

- the 12 parts are Codebase
- Dependencies
- Config
- Backing services
- Build, release, run
- Processes
- Port binding
- Concurrency
- Disposability
- Dev/prod parity
- Logs
- Admin processes

- Its main rule is to store configuration in the environment. Following this recommendation will give us strict separation of config from code.

## SSH

- secure shell

- a remote administration protocol that allows users to control and modify their remote servers over the Internet.

- for windows use putty.

- for mac.. 
`ssh {user}@{host}`

- user is the account you wish to access
- host refers to the computer you want to access
- when you hit enter you will be asked for a password.

- Symmetric encryption is a form of encryption where a secret key is used for both encryption and decryption of a message by both the client and the host. 

- Unlike symmetrical encryption, asymmetrical encryption uses two separate keys for encryption and decryption. 

- hashing - a unique value of a fixed length for each input that shows no clear trend which can exploited.

- SSH uses hashes to verify the authenticity of messages. This is done using HMACs, or Hash-based Message Authentication Codes. This ensures that the command received is not tampered with in any way.

