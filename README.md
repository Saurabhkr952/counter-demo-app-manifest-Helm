# counter-demo-app-manifest-Helm

For configuring argo 
sed -i 's+saurabhkr952/counter-demo-app:.*+saurabhkr952/counter-demo-app:${{BUILD_NUMBER}}+g' /templates/demo-counter-app.yaml
