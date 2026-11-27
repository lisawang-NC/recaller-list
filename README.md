# Recaller List
Builds cosdpprd.glall_user.recallerlist: customers whose first recall is within 0-30 days.
- Notebook: src/recaller_list
- Job: resources/recaller_list.job.yml
- Deploy: databricks bundle deploy -t dev
- Contains PII (PhoneNumber): never commit notebook outputs.