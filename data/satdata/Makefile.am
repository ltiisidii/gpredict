gpredict_satdir = $(pkgdatadir)/data/satdata

# Resolve catalog files in the source tree for out-of-tree builds (distcheck).
gpredict_sat_DATA = satellites.dat $(notdir $(wildcard $(srcdir)/*.cat))

EXTRA_DIST = $(gpredict_sat_DATA)
