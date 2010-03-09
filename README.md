# Using

    gem install can_write

Make file named can_write in your application root and write simple commands, such as:

    
    ['tmp', 'log'].should_be_writable.by_user 'www-data'

    %w{app lib}.should_be_readable.by_user 'www-data'

    %w{script/generate script/about}.should_be_executable.by_user 'www-data'

Run in your application filder

    can_write

