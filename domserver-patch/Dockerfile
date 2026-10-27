FROM domjudge/domserver:8.2.3

RUN apt-get update \
&& apt-get install -y --only-upgrade 'php8.2-*' \
&& rm -rf /var/lib/apt/lists/*