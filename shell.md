cat all.txt |sed "s|images|labels|g;s|.jpg$|.txt|g;s|.png$|.txt|g" | xargs -i grep -l "^3" {}
