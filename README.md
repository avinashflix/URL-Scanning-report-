1. Need to understand what are the techstack's are used in the website.

i) Linux Command : whatweb 
ii) Wappalyzer Extension

2. Katana Command for discover all endpoints ?

katana -u target.com  -d 5 -jc | grep '\.js$' | tee alljs.txt


