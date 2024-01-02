# eda-rulebooks
  
The following curl command can be used to trigger the "Update Prod Servers" Rulebook Activation in EDA controller:
```
curl --header "Content-Type: application/json" \
  --request POST \
  --data '{"message":"force-update"}' \
  eda-controller.mikerkelly.com:5000
```
  
