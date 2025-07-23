Usefull Commands

index.tml
aws s3 cp index.html s3://saiteja-pickles-site/index.html --content-type "text/html" --metadata-directive REPLACE
upload: .\index.html to s3://saiteja-pickles-site/index.html
 
style.css
aws s3 cp style.css s3://saiteja-pickles-site/style.css --content-type "text/css" --metadata-directive REPLACE
 
image:
aws s3 cp images/mutton.jpg s3://saiteja-pickles-site/images/mutton.jpg --content-type "image/jpeg"
