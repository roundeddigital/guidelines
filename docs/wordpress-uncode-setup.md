### Increase WP Memory limit
 - In Wordpress > wp-includes > default-constants.php
  - [ ] On line 42, change WP_MEMORY_LIMIT from 40M to 96M

    ```
upload_max_filesize = 200M
post_max_size = 205M
max_execution_time = 3000
max_input_time = 5000
memory_limit = 512M
max_input_vars = 3000
Allow_url_fopen = ON`
```

File Located: root > php > 7.0 > phprc
