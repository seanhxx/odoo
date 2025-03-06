# Environment Setup

## 1st time run to initialize the database
```bash
python ./odoo-bin -d postgres --db_host=localhost --db_port=5432 --db_user=odoo --db_password=odoo -i base --addons-path=addons,../openeducat_erp
```

## Run the server
```bash
python ./odoo-bin -d postgres --db_host=localhost --db_port=5432 --db_user=odoo --db_password=odoo --addons-path=addons,../openeducat_erp
```