# springdataflow-poc
##Getting started
* Run 'docker-compose up'
* Open the dashboard at http://localhost:9393/dashboard
* Use 'Create Stream' under STREAMS Tab to define and deploy a stream.
* To view the stream logs, copy the path in the "stdout" text box on the dashboard and in another console type: docker exec -it dataflow-server tail -f *COPIED-STDOUT-PATH*

##Update app JAR
* Move app.jar to apps folder
* Update vtr.processor file with correct jar name
* Restart docker