    location / {
        proxy_pass http://127.0.0.1:3580;
    }

    location /poll {
        proxy_pass http://127.0.0.1:3581;
    } 
