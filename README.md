1. Need to understand what are the techstack's are used in the website.

i) Linux Command : whatweb 
ii) Wappalyzer Extension

2. Katana Command for discover all endpoints ?

katana -u target.com  -d 5 -jc | grep '\.js$' | tee alljs.txt

3. Using this command we can see the status code for all URLs

katana -list endpoints.txt | httpx -status-code -o status_output.txt

4. Filter only 200 response code

grep "\[200\]"  gau_status_output.txt > filtered_200.txt 
