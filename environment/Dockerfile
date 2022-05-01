FROM ruby:3.0.0

WORKDIR /home

COPY aplicacao/ /home
COPY environment/entrypoint-server.sh /

RUN bundle install

ENTRYPOINT ["bash"]

CMD ["/entrypoint-server.sh"]
