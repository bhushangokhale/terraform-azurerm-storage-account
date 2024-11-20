# Enable static website
enable_static_website = false

# Enable cross tenant replication
cross_tenant_replication_enabled = false

# Encryption scopes
encryption_scopes = {
  scope1 = {
    enable_infrastructure_encryption = true
    source = "Microsoft.KeyVault"
  }
  scope2 = {
    source = "Microsoft.Storage"
  }
}

# Other variables used in main.tf
name = "mybgstorage09"
resource_group_name = "LearnRG-01"
location = "East US"
account_kind = "StorageV2"
account_tier = "Standard"
replication_type = "GRS"
access_tier = "Hot"
tags = {
  environment = "production"
}

enable_hns = true
enable_sftp = false
enable_large_file_share = false
allow_nested_items_to_be_public = false
enable_https_traffic_only = true
min_tls_version = "TLS1_2"
nfsv3_enabled = false
infrastructure_encryption_enabled = true
shared_access_key_enabled = true
default_to_oauth_authentication = false