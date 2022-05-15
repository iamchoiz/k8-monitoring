upgrade:
	helm upgrade -i prometheus \
	  -n monitoring \
	  --create-namespace \
	  -f values.yaml \
	  prometheus-community/prometheus
	  

delete:
	helm delete -n monitoring prometheus

template:
	helm template -n monitoring -f values.yaml prometheus-community/prometheus
