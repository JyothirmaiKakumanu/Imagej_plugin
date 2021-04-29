

### Eclipse: To ensure that Maven copies the plugin to your ImageJ folder

1. Go to _Run Configurations..._
2. Choose _Maven Build_
3. Add the following parameter:
    - name: `scijava.app.directory`
    - value: `/path/to/ImageJ.app/`

This ensures that the final `.jar` file will also be copied to
your ImageJ plugins folder everytime you run the Maven build.
