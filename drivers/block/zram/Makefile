# SPDX-License-Identifier: GPL-2.0-only
zram-y	:=	zcomp.o zram_drv.o
zram-$(CONFIG_ZRAM_BACKEND_LZO)		+= backend_lzorle.o backend_lzo.o
zram-$(CONFIG_ZRAM_BACKEND_LZ4)		+= backend_lz4.o
zram-$(CONFIG_ZRAM_BACKEND_LZ4HC)	+= backend_lz4hc.o
zram-$(CONFIG_ZRAM_BACKEND_ZSTD)	+= backend_zstd.o
zram-$(CONFIG_ZRAM_BACKEND_DEFLATE)	+= backend_deflate.o
zram-$(CONFIG_ZRAM_BACKEND_842)		+= backend_842.o
zram-$(CONFIG_ZRAM_DEDUP)	+=	zram_dedup.o

obj-$(CONFIG_ZRAM)	+=	zram.o

#ifdef OPLUS_FEATURE_ZRAM_WRITEBACK
obj-$(CONFIG_ZWB_HANDLE) += zwb_handle/
#endif /* OPLUS_FEATURE_ZRAM_WRITEBACK */

zram-$(CONFIG_HYBRIDSWAP) += hybridswap/hybridswap_main.o
zram-$(CONFIG_HYBRIDSWAP_SWAPD) += hybridswap/hybridswap_swapd.o
zram-$(CONFIG_HYBRIDSWAP_ASYNC_COMPRESS) += hybridswap/hybridswap_akcompress.o
zram-$(CONFIG_HYBRIDSWAP_CORE) += hybridswap/hybridswap_area.o hybridswap/hybridswap_core.o hybridswap/hybridswap_ctrl.o hybridswap/hybridswap_list.o hybridswap/hybridswap_lru_rmap.o hybridswap/hybridswap_manager.o hybridswap/hybridswap_perf.o hybridswap/hybridswap_schedule.o hybridswap/hybridswap_stats.o
