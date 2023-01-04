# python
python

#### 使用polysh同时操作多台机器

```bash
polysh --ssh 'ssh -i /Users/zhengdongqi/.ssh/mengmai.pem' --user=root --hosts-file=host.txt
```

```bash
# host.txt
host1
host2
```

