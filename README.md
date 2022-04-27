Starting:

    $ docker-compose up

Current error:

    ❯ kcat -b 127.0.0.1:19092 -L
    %6|1651043703.259|FAIL|rdkafka#producer-1| [thrd:127.0.0.1:19092/bootstrap]: 127.0.0.1:19092/bootstrap: Disconnected while requesting ApiVersion: might be caused by incorrect security.protocol configuration (connecting to a SSL listener?) or broker version is < 0.10 (see api.version.request) (after 1ms in state APIVERSION_QUERY)
    