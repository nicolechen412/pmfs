obj-$(CONFIG_LUSTRE_FS) += lustre.o
obj-$(CONFIG_LUSTRE_FS) += llite_lloop.o
lustre-y := dcache.o dir.o file.o llite_close.o llite_lib.o llite_nfs.o \
	    rw.o lproc_llite.o namei.o symlink.o llite_mmap.o \
	    xattr.o remote_perm.o llite_rmtacl.o llite_capa.o \
	    rw26.o super25.o statahead.o \
	    ../lclient/glimpse.o ../lclient/lcommon_cl.o ../lclient/lcommon_misc.o \
	    vvp_dev.o vvp_page.o vvp_lock.o vvp_io.o vvp_object.o

llite_lloop-y := lloop.o


ccflags-y := -I$(src)/../include
