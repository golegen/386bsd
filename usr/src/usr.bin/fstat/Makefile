#	@(#)Makefile	5.5 (Berkeley) 4/23/91

PROG=	fstat
# SRCS=	fstat.c devname.c
SRCS=	fstat.c
NONSTDINC+= $(INCOLDBSD) $(INCKERNEL) $(INCFS)
#CFLAGS+=-I/sys
.PATH:	${.CURDIR}/../../bin/ps
DPADD=	${LIBUTIL}
LDADD=	-lutil
BINGRP=	kmem
BINMODE=2555

.include <bsd.prog.mk>
