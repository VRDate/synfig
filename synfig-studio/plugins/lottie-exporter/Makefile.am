PLUGIN_NAME = lottie-exporter

EXTRA_FILES = bodymovin.js \
			  canvas.py \
			  settings.py \
			  bodymovin_5.6.5.js \
			  export_without_variable_width.py
			  
plugindir = $(synfig_datadir)/plugins/$(PLUGIN_NAME)
plugin_DATA = \
			  $(PLUGIN_NAME).py \
			  plugin.xml \
			  $(EXTRA_FILES)

@INTLTOOL_XML_RULE@

EXTRA_DIST = \
	$(PLUGIN_NAME).py \
	plugin.xml.in \
	$(EXTRA_FILES)

MAINTAINERCLEANFILES = Makefile.in
DISTCLEANFILES = plugin.xml

SUBDIRS = \
		  common \
		  effects \
          helpers \
          layers \
          properties \
          shapes \
		  sources \
		  synfig
