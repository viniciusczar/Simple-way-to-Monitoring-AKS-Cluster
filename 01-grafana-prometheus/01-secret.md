kubectl create secret generic azure-files-secret \
  --from-literal=azurestorageaccountname=AccountFileNameHere \
  --from-literal=azurestorageaccountkey=LongHashAccountKeyHere \
  --namespace=monitoring