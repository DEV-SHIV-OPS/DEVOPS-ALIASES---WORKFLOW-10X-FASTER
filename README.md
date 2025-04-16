DEVOPS ALIASES FOR FASTER WORKFLOW

DEVOPS ALIASES
•	All the aliases 
•	A clear explanation of why aliases are useful in DevOps workflows 
________________________________________DevOps Aliases for Faster Workflow

Hi, I'm Shivam Vishwakarma 

As a DevOps Engineer, time is everything. Repeating long terminal commands can slow down productivity. That’s why I use aliases — simple shortcuts that map long or frequently used commands to short, memorable ones.


…………….

Why Aliases Matter in DevOps

Speed Up Workflow: Saves time by shortening commonly used commands.

Reduce Typing Errors: Short, predefined commands reduce the chance of mistakes.

Improve Efficiency: Execute repetitive tasks faster with a single keyword.

Standardization: Shared aliases create consistency in team environments.

Less Cognitive Load: No need to remember long syntax every time.

Add these to your `.bashrc`, `.zshrc`, or `.profile`, then run `source ~/.bashrc` or `source ~/.zshrc` to apply.


Kubernetes Aliases
alias k='kubectl'                            # Short alias for kubectl
alias kgp='kubectl get pods'                 # View all running pods
alias kgs='kubectl get svc'                  # List services
alias kgn='kubectl get nodes'                # Show cluster nodes
alias kga='kubectl get all'                  # Get all resources
alias kgd='kubectl get deployments'          # List deployments
alias kctx='kubectl config use-context'      # Switch Kubernetes context
alias kns='kubectl config set-context --current --namespace'  # Set default namespace
alias kex='kubectl exec -it'                 # Exec into a running pod
alias kl='kubectl logs'                      # View logs
alias klf='kubectl logs -f'                  # Follow live logs
alias kaf='kubectl apply -f'                 # Apply a YAML file
alias kdf='kubectl delete -f'                # Delete a resource from file
alias ktop='kubectl top pods'                # View pod metrics
alias ktopn='kubectl top nodes'              # View node metrics
________________________________________
Docker Aliases
alias d='docker'
alias dps='docker ps'                        # List running containers
alias dpsa='docker ps -a'                    # List all containers
alias dimg='docker images'                   # List images
alias drm='docker rm'                        # Remove container
alias drmi='docker rmi'                      # Remove image
alias dex='docker exec -it'                  # Exec into container
alias db='docker build -t'                   # Build Docker image
alias dup='docker-compose up -d'             # Start services
alias ddown='docker-compose down'            # Stop services
________________________________________
Git Aliases
alias gst='git status'                       # Show repo status
alias gpl='git pull'                         # Pull changes
alias gps='git push'                         # Push changes
alias gcm='git commit -m'                    # Commit with message
alias gco='git checkout'                     # Switch branch
alias gb='git branch'                        # List branches
alias gaa='git add .'                        # Add all files
alias glog='git log --oneline --graph --all' # Visual log history
________________________________________
Helm Aliases
alias h='helm'
alias hi='helm install'                      # Install a chart
alias hu='helm upgrade'                      # Upgrade a release
alias hl='helm list'                         # List releases
alias hls='helm ls --all-namespaces'         # List in all namespaces
alias hdel='helm delete'                     # Delete a release
alias hrepo='helm repo list'                 # Show repo list
alias hrepoa='helm repo add'                 # Add a repo
alias hrepou='helm repo update'              # Update repo index
________________________________________
Terraform Aliases
alias tf='terraform'
alias tfi='terraform init'                   # Initialize configuration
alias tfp='terraform plan'                   # Show execution plan
alias tfa='terraform apply'                  # Apply changes
alias tfd='terraform destroy'                # Destroy infrastructure
alias tfv='terraform validate'               # Validate configuration
alias tffmt='terraform fmt'                  # Format .tf files
________________________________________
Ansible Aliases
alias ans='ansible'
alias ap='ansible-playbook'                  # Run playbook
alias av='ansible -m'                        # Run ad-hoc module
alias ai='ansible-inventory --list -y'       # View inventory
________________________________________
AWS CLI Aliases
alias awsls='aws s3 ls'                      # List S3 buckets or contents
alias awscp='aws s3 cp'                      # Copy files to/from S3
alias awsrm='aws s3 rm'                      # Remove file from S3
alias awsec2='aws ec2 describe-instances'    # List EC2 instances
alias awsiam='aws iam list-users'            # List IAM users
alias awssg='aws ec2 describe-security-groups'  # Show security groups
________________________________________
Jenkins CLI Aliases
alias jcli='java -jar jenkins-cli.jar'
alias jjob='java -jar jenkins-cli.jar build'     # Trigger a build
alias jlog='java -jar jenkins-cli.jar console'   # View job output
________________________________________
Linux & Shell Utilities
alias cls='clear'                            # Clear the screen
alias ll='ls -alF'                           # Detailed list
alias la='ls -A'                             # List hidden files
alias l='ls -CF'                             # Column format
alias dfh='df -h'                            # Disk usage (human-readable)
alias duh='du -sh'                           # Folder size summary
alias topu='top -u $(whoami)'               # Show top for current user
alias grep='grep --color=auto'              # Highlight matches
________________________________________
How to Use These Aliases
1.	Copy and paste your preferred aliases into your shell config file:
o	~/.bashrc (for Bash)
o	~/.zshrc (for Zsh)
2.	Reload the file using:
source ~/.bashrc
# or
source ~/.zshrc
This will make all your DevOps tool interactions smoother, faster, and more reliable.



Thank you
Shivam vishwakarma 
Follow me: https://www.linkedin.com/in/shivamvishwakarm1/ 

