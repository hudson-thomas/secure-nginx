# Nginx
This is a more secure version of nginx. Out of the box, it comes with a method to obfuscate nginx and version number. More features are being added all the time, one of which, DDoS protection, is set to be released in the coming days. Remember: this project is still a work in progress and no feature is sure to work 100% of the time. For now I would only recommed using this if you know what you are doing, or are okay with a mostly normal nginx.

nginx is not very secure out of the box. This project hopes to fix that. In order to do that, I need your help. I am only aware of a few issues and fixes, so I need YOU to contribute what you know.


### Basic Install

sudo apt-get install libpcre3 libpcre3-dev zlib1g zlib1g-dev libssl-dev

./configure --without-http_autoindex_module --without-http_ssi_module

make

make install


### Legal

This software is almost a direct copy of the main nginx repo, and therefore carries the same license. So yes, I am allowed to make a repo like this, as long as I keep the license the same and don't steal the trademark. That's the legal stuff out of the way, so let's move onto contributing.


### Contributing
It's pretty simple really, simply fork the repo, make a fix, and submit a pull request with a fair amount of detail. Due to the sensitivity of such a project, PR's may take some time to be accepted in order to perform a thorough inspection. To increase the chance of getting approved, follow this list:
* Make useful changes. This early into development, I am willing to inspect small changes, but going into the future please ensure changes are of use to the project (no spam).
* Provide lots of detail in a pull request. This is a big one. If I don't know what you are trying to fix, I might see it as spam, so please describe what your change intends to do.
* Don't be scared of doing something wrong! We all have to start somewhere, and with Hacktoberfest right around the corner, I would be more than happy to see some beginners contribute. That's the beauty of open-source, anyone of any skill level can contribute. I check all PR before I release them to the wild, so if I see something unusual, I will provide feedback.
* Remember this repo is for creating a more secure version of nginx. 
