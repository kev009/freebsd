# $FreeBSD$

.include <bsd.own.mk>

.PATH: ${.CURDIR}/../../netpfil/npf

KMOD=	npf
SRCS=	npf.c npf_conf.c npf_ctl.c npf_handler.c npf_mbuf.c npf_bpf.c \
	npf_ruleset.c npf_rproc.c npf_tableset.c npf_tableset_ptree.c \
	npf_if.c npf_inet.c npf_conn.c npf_conndb.c npf_state.c \
	npf_state_tcp.c npf_nat.c npf_alg.c npf_sendpkt.c npf_worker.c \

.include <bsd.kmod.mk>
