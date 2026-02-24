# CLI commands and outputs

# Validate Deployment

az deployment group validate --resource-group 20251229-PWC-Azure --template-file arm.json --parameters "@parameter.json" -o table

# Expected output

Result CorrelationId

---

Succeeded 28cd5441-b5ce-4242-9cb0-65be4de4ffaf

# Deploy Template

az deployment group create --resource-group 20251229-PWC-Azure --template-file arm.json --parameters "@parameter.json" -o table

# Expected output
