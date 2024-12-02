# work

871c010f-5e61-4fb1-83ac-98610a7e9110

az aks get-credentials --resource-group rg-dev-SupplyChaincontroltower --name kub-dev-scm --overwrite-existing

grafana-20240917170403


sha256:f916c4f2e917f0ca3a4789b181ab8f58529cc50ed1c2379272dfc26ed057afe9

helm uninstall aks-managed-azure-monitor-metrics -n kube-system

helm list -n kube-system

az aks show --name kub-dev-scm --resource-group rg-dev-SupplyChaincontroltower --query addonProfiles.omsagent

az aks start --name kub-dev-scm --resource-group rg-dev-SupplyChaincontroltower

az network private-endpoint show --name <private-endpoint-name> --resource-group rg-dev-SupplyChaincontroltower

