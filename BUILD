licenses(["notice"])

cc_library(
  name = 'libevent',
  visibility = ['//visibility:public'],
  deps = [
    '//external:libssl',
  ],
  includes = [
    '.',
    'include',
    '__build__/linux/include',
  ],
  srcs = [
    'buffer.c',
    'bufferevent.c',
    'bufferevent_filter.c',
    'bufferevent_openssl.c',
    'bufferevent_pair.c',
    'bufferevent_ratelim.c',
    'bufferevent_sock.c',
    'epoll.c',
    'evdns.c',
    'event.c',
    'event_tagging.c',
    'evmap.c',
    'evrpc.c',
    'evthread.c',
    'evthread_pthread.c',
    'evutil.c',
    'evutil_rand.c',
    'http.c',
    'listener.c',
    'log.c',
    'poll.c',
    'select.c',
    'signal.c',
    'strlcpy.c',
  ],
  copts = [
    '-isystemlibevent/compat',
  ]
)
