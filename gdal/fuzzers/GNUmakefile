
include ../GDALmake.opt

OBJ	=	gdal_fuzzer.o ogr_fuzzer.o shape_fuzzer.o mitab_tab_fuzzer.o \
		mitab_mif_fuzzer.o wkb_import_fuzzer.o wkt_import_fuzzer.o \
		osr_set_from_user_input_fuzzer.o

CPPFLAGS	:=	$(CPPFLAGS)

default:	$(OBJ:.o=.$(OBJ_EXT))

clean:
	$(RM) *.o $(O_OBJ)

