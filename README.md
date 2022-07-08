
This is a fork of the excellent pereorga/minimalist-web-notepad that just havs just single file.
I'm planing remove the code that i dont need to make it happen.

demo sj.orz.us


location / {
    rewrite ^/([a-zA-Z0-9_-]+)$ /index.php?note=a;
}
