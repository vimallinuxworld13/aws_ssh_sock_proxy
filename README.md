# aws_ssh_sock_proxy

# ssh -i key_aws_california.pem  ec2-user@54.215.128.17  -N -D 9090


"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --user-data-dir="%USERPROFILE%\proxy-profile" --proxy-server="socks5://localhost:9090"


speed test using curl:
curl -s -o /dev/null -w "%{time_total}\n" http://54.215.128.17/
