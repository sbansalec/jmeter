# lyc_jmeter

Note : you need run these command from script folder and need to replace jmeter with actual jmeter path

1)command to run POC script

jmeter -Jhttpsampler.ignore_failed_embedded_resources=true -Jjmeter.save.saveservice.output_format=xml -JBASE_URL_1=cloudbourne-dev-mbk-nginx-1-0.0314f142.lowtouch.cloud -n -t Create_MKB.jmx -l testresults.jtl
