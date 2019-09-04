# Catch-the-Phishing-Domain-before-they-start-Campaign
Catching the phishing domain looks legitimate/similar to your organization through Certstream. Certstream provides live streaming of newly created SSL.

So here, what we need is to monitor SSL certificate of All the domains created worldwide in real time.
Yes, it is possible. So whenever bad guys creates similar domain to your organization  with SSL certificate to target you, You can catch them at the same time.

This facility is provided by "https://certstream.calidog.io/". Certstream is real-time certificate transparency logs and I created a script to use certstream to fetch the real time logs and look for organization which you are working in.

Requirements for this script to run:

better with python3.6
pip install requirements.txt (python dependancies) 

termcolor==1.1.0
certstream==1.8
entropy==0.10
tqdm==4.19.4
tld==0.7.9
python_Levenshtein==0.12.0
PyYAML==5.1.2
