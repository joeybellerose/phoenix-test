FROM livebook/livebook

RUN apt update -y
RUN apt install -y inotify-tools

CMD ["cd", "demo"]
CMD ["mix", "phx.server"]