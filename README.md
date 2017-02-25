# config.yml

```
${server_name}:
  box: "${box_name}"
  hosts:
    - hostname: "${hostname}"
      lips:
        - "${local_ip_addr}"
  syncs:
    - host: "${sync_host_dir}"
      guest: "${sync_guest_dir}"
      dmode: "${dir_mode}"
      fmode: "${file_mode}"
  provision:
    - "${provision_shell}"
	itamae:
		- recipe: ${itamae_script}
		  json: ${itamae_json_node}
```
