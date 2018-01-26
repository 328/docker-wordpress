`docker-compose up -d` で起動するとwp-networkが生成されるが  
下記のように`dockerwordpress_wp-network`という感じでディレクトリ名もついてきてしまうため、解決したい。

ネットワーク名が `dockerwordpress_wp-network` -> `wp-network` になってくれると嬉しい!

```
$ docker network ls | grep wp-network
2d352f9fa99a        dockerwordpress_wp-network       bridge              loca
```
