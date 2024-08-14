FROM redpandadata/connectors:v1.0.28

ENV CONNECT_PLUGIN_PATH "/opt/kafka/connect-plugins"

USER root

RUN mkdir -p $CONNECT_PLUGIN_PATH && \
    cd $CONNECT_PLUGIN_PATH && \
    curl -L https://github.com/Azure/kafka-sink-azure-kusto/releases/download/v4.0.10/microsoftcorporation-kafka-sink-azure-kusto-4.0.10.zip \
        -o microsoftcorporation-kafka-sink-azure-kusto.zip && \
    unzip microsoftcorporation-kafka-sink-azure-kusto.zip && \
    rm microsoftcorporation-kafka-sink-azure-kusto.zip && ls -al

USER redpanda
