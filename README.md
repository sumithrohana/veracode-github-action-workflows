This repository contains sample GitHub Action Workflow yml files for automating Veracode security scanning through GitHub CI/CD pipelines.

Pre-Requisites

      Create Secrets 
            VID: <veracode API user ID>
            VKey: <veracode API user secret>
            SRCCLR_API_TOKEN: <veracode SCA token>
      
      Replace followings with your specific project values
            <repo_URL>
            <repo_name>
            <branch_name>
            <binary_name>
            <veracode_application_name>
            <veracode_sandbox_name>
     
      Change dependency library versions with your choice
            eg., <java-version>, <python-version>, <node-version> etc.,
            

