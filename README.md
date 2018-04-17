# ansibel_windows


#### Command
```
export GUID=`hostname | awk -F"." '{print $2}'`

ansible-playbook ad.yml -e "GUID=${GUID}"
```