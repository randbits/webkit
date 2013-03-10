include $(srcdir)/Source/WebCore/GNUmakefile.list.am

WEBCORE_CSS_PROPERTY_NAMES := $(WebCore)/css/CSSPropertyNames.in
WEBCORE_CSS_VALUE_KEYWORDS := $(WebCore)/css/CSSValueKeywords.in

webcore_cppflags += \
	-I$(srcdir)/Source/ThirdParty/ANGLE/src \
	-I$(srcdir)/Source/ThirdParty/ANGLE/include \
	-I$(srcdir)/Source/ThirdParty/ANGLE/include/GLSLANG \
	-I$(srcdir)/Source/WebCore \
	-I$(srcdir)/Source/WebCore/Modules/filesystem \
	-I$(srcdir)/Source/WebCore/Modules/gamepad \
	-I$(srcdir)/Source/WebCore/Modules/geolocation \
	-I$(srcdir)/Source/WebCore/Modules/indexeddb \
	-I$(srcdir)/Source/WebCore/Modules/mediasource \
	-I$(srcdir)/Source/WebCore/Modules/mediastream \
	-I$(srcdir)/Source/WebCore/Modules/notifications \
	-I$(srcdir)/Source/WebCore/Modules/protocolhandler \
	-I$(srcdir)/Source/WebCore/Modules/quota \
	-I$(srcdir)/Source/WebCore/Modules/webaudio \
	-I$(srcdir)/Source/WebCore/Modules/webdatabase \
	-I$(srcdir)/Source/WebCore/Modules/websockets \
	-I$(srcdir)/Source/WebCore/accessibility \
	-I$(srcdir)/Source/WebCore/bindings \
	-I$(srcdir)/Source/WebCore/bindings/generic \
	-I$(srcdir)/Source/WebCore/bindings/js \
	-I$(srcdir)/Source/WebCore/bridge \
	-I$(srcdir)/Source/WebCore/bridge/c \
	-I$(srcdir)/Source/WebCore/bridge/jni/jsc \
	-I$(srcdir)/Source/WebCore/bridge/jsc \
	-I$(srcdir)/Source/WebCore/css \
	-I$(srcdir)/Source/WebCore/dom \
	-I$(srcdir)/Source/WebCore/dom/default \
	-I$(srcdir)/Source/WebCore/editing \
	-I$(srcdir)/Source/WebCore/fileapi \
	-I$(srcdir)/Source/WebCore/history \
	-I$(srcdir)/Source/WebCore/html \
	-I$(srcdir)/Source/WebCore/html/canvas \
	-I$(srcdir)/Source/WebCore/html/parser \
	-I$(srcdir)/Source/WebCore/html/shadow \
	-I$(srcdir)/Source/WebCore/html/track \
	-I$(srcdir)/Source/WebCore/inspector \
	-I$(srcdir)/Source/WebCore/loader \
	-I$(srcdir)/Source/WebCore/loader/appcache \
	-I$(srcdir)/Source/WebCore/loader/archive \
	-I$(srcdir)/Source/WebCore/loader/cache \
	-I$(srcdir)/Source/WebCore/loader/icon \
	-I$(srcdir)/Source/WebCore/mathml \
	-I$(srcdir)/Source/WebCore/page \
	-I$(srcdir)/Source/WebCore/page/animation \
	-I$(srcdir)/Source/WebCore/page/scrolling \
	-I$(srcdir)/Source/WebCore/platform \
	-I$(srcdir)/Source/WebCore/platform/animation \
	-I$(srcdir)/Source/WebCore/platform/audio \
	-I$(srcdir)/Source/WebCore/platform/graphics \
	-I$(srcdir)/Source/WebCore/platform/graphics/filters \
	-I$(srcdir)/Source/WebCore/platform/graphics/filters/arm \
	-I$(srcdir)/Source/WebCore/platform/graphics/gpu \
	-I$(srcdir)/Source/WebCore/platform/graphics/opengl \
	-I$(srcdir)/Source/WebCore/platform/graphics/opentype \
	-I$(srcdir)/Source/WebCore/platform/graphics/transforms \
	-I$(srcdir)/Source/WebCore/platform/image-decoders \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/bmp \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/gif \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/ico \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/jpeg \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/webp \
	-I$(srcdir)/Source/WebCore/platform/image-decoders/png \
	-I$(srcdir)/Source/WebCore/platform/leveldb \
	-I$(srcdir)/Source/WebCore/platform/linux \
	-I$(srcdir)/Source/WebCore/platform/mediastream \
	-I$(srcdir)/Source/WebCore/platform/mediastream/gstreamer \
	-I$(srcdir)/Source/WebCore/platform/mock \
	-I$(srcdir)/Source/WebCore/platform/network \
	-I$(srcdir)/Source/WebCore/platform/sql \
	-I$(srcdir)/Source/WebCore/platform/text \
	-I$(srcdir)/Source/WebCore/platform/text/transcoder \
	-I$(srcdir)/Source/WebCore/platform/win \
	-I$(srcdir)/Source/WebCore/plugins \
	-I$(srcdir)/Source/WebCore/plugins/win \
	-I$(srcdir)/Source/WebCore/rendering \
	-I$(srcdir)/Source/WebCore/rendering/mathml \
	-I$(srcdir)/Source/WebCore/rendering/style \
	-I$(srcdir)/Source/WebCore/rendering/svg \
	-I$(srcdir)/Source/WebCore/storage \
	-I$(srcdir)/Source/WebCore/svg \
	-I$(srcdir)/Source/WebCore/svg/animation \
	-I$(srcdir)/Source/WebCore/svg/graphics \
	-I$(srcdir)/Source/WebCore/svg/graphics/filters \
	-I$(srcdir)/Source/WebCore/svg/properties \
	-I$(srcdir)/Source/WebCore/testing \
	-I$(srcdir)/Source/WebCore/testing/js \
	-I$(srcdir)/Source/WebCore/websockets \
	-I$(srcdir)/Source/WebCore/workers \
	-I$(srcdir)/Source/WebCore/xml \
	-I$(srcdir)/Source/WebCore/xml/parser \
	-I$(top_builddir)/WebCore/bindings/js \
	-I$(top_builddir)/DerivedSources/WebCore \
	-I$(top_builddir)/DerivedSources \
	-I$(top_builddir)/DerivedSources/JavaScriptCore \
	-DDATA_DIR=\"${datadir}\"

webcoregtk_cppflags += \
	-DWEBKITGTK_API_VERSION_STRING=\"@WEBKITGTK_API_VERSION@\" \
	-DWTF_USE_SOUP=1 \
	-I$(srcdir)/Source/WebCore/accessibility/gtk \
	-I$(srcdir)/Source/WebCore/loader/gtk \
	-I$(srcdir)/Source/WebCore/page/gtk \
	-I$(srcdir)/Source/WebCore/platform/cairo \
	-I$(srcdir)/Source/WebCore/platform/audio/gstreamer \
	-I$(srcdir)/Source/WebCore/platform/geoclue \
	-I$(srcdir)/Source/WebCore/platform/graphics/cairo \
	-I$(srcdir)/Source/WebCore/platform/graphics/glx \
	-I$(srcdir)/Source/WebCore/platform/graphics/gstreamer \
	-I$(srcdir)/Source/WebCore/platform/graphics/gtk \
	-I$(srcdir)/Source/WebCore/platform/gtk \
	-I$(srcdir)/Source/WebCore/platform/network/soup \
	-I$(srcdir)/Source/WebCore/platform/text/gtk

# ---
# Features enabled by default at compilation time
# ---
FEATURE_DEFINES += ENABLE_SMOOTH_SCROLLING=1
webcore_cppflags += -DENABLE_SMOOTH_SCROLLING=1

# ---
# Channel mesaging support
# ---
if ENABLE_CHANNEL_MESSAGING
FEATURE_DEFINES += ENABLE_CHANNEL_MESSAGING=1
webcore_cppflags += -DENABLE_CHANNEL_MESSAGING=1
endif # END ENABLE_CHANNEL_MESSAGING

# ---
# Fast Mobile Scrolling
# ---
if ENABLE_FAST_MOBILE_SCROLLING
FEATURE_DEFINES += ENABLE_FAST_MOBILE_SCROLLING=1
webcore_cppflags += -DENABLE_FAST_MOBILE_SCROLLING=1
endif # END ENABLE_FAST_MOBILE_SCROLLING

# ---
# FreeType font backend
# ---
if USE_FREETYPE
webcoregtk_cppflags += \
	-DWTF_USE_FREETYPE=1 \
	-I$(srcdir)/Source/WebCore/platform/graphics/freetype
endif # END USE_FREETYPE

# ---
# Pango font backend
# ---
if USE_PANGO
webcoregtk_cppflags += \
	-DWTF_USE_PANGO=1 \
	-I$(srcdir)/Source/WebCore/platform/graphics/pango
endif # END USE_PANGO

# ---
# Windows plugin support
# ---
if TARGET_WIN32
webcoregtk_cppflags += \
	-I$(srcdir)/Source/WebCore/platform/graphics/win
endif # END TARGET_WIN32

# ----
# HTML Details Element
# ----
if ENABLE_DETAILS_ELEMENT
FEATURE_DEFINES += ENABLE_DETAILS_ELEMENT=1
webcore_cppflags += -DENABLE_DETAILS_ELEMENT=1
endif # END ENABLE_DETAILS_ELEMENT

# ----
# HTML Meter Element
# ----
if ENABLE_METER_ELEMENT
FEATURE_DEFINES += ENABLE_METER_ELEMENT=1
webcore_cppflags += -DENABLE_METER_ELEMENT=1
endif # END ENABLE_METER_ELEMENT

# ----
# HTML Progress Element
# ----
if ENABLE_PROGRESS_ELEMENT
FEATURE_DEFINES += ENABLE_PROGRESS_ELEMENT=1
webcore_cppflags += -DENABLE_PROGRESS_ELEMENT=1
endif # END ENABLE_PROGRESS_ELEMENT

# ----
# JavaScript Debugger/Profiler
# ----
if ENABLE_JAVASCRIPT_DEBUGGER
FEATURE_DEFINES += ENABLE_JAVASCRIPT_DEBUGGER=1
webcore_cppflags += -DENABLE_JAVASCRIPT_DEBUGGER=1
else
webcore_cppflags += -DENABLE_JAVASCRIPT_DEBUGGER=0
endif # END ENABLE_JAVASCRIPT_DEBUGGER

# ----
# Gamepad support
# ---
if ENABLE_GAMEPAD
FEATURE_DEFINES += ENABLE_GAMEPAD=1
webcore_cppflags += -DENABLE_GAMEPAD=1
else
webcore_cppflags += -DENABLE_GAMEPAD=0
endif # END ENABLE_GAMEPAD

# ----
# Database Support
# ----
if ENABLE_SQL_DATABASE
FEATURE_DEFINES += ENABLE_SQL_DATABASE=1
webcore_cppflags += -DENABLE_SQL_DATABASE=1
else
webcore_cppflags += -DENABLE_SQL_DATABASE=0
endif # END ENABLE_SQL_DATABASE

# ----
# HTML5 datalist Support
# ----
if ENABLE_DATALIST_ELEMENT
FEATURE_DEFINES += ENABLE_DATALIST_ELEMENT=1
webcore_cppflags += -DENABLE_DATALIST_ELEMENT=1
endif # END ENABLE_DATALIST_ELEMENT

# ----
# HTML5 data transfer items support
# ----
if ENABLE_DATA_TRANSFER_ITEMS
FEATURE_DEFINES += ENABLE_DATA_TRANSFER_ITEMS=1
webcore_cppflags += -DENABLE_DATA_TRANSFER_ITEMS=1
endif # END ENABLE_DATA_TRANSFER_ITEMS

# ----
# HTML5 <style scoped> support
# ----
if ENABLE_STYLE_SCOPED
FEATURE_DEFINES += ENABLE_STYLE_SCOPED=1
webcore_cppflags += -DENABLE_STYLE_SCOPED=1
endif # END ENABLE_STYLE_SCOPED

# ----
# Indexed Database API support
# ----
if ENABLE_INDEXED_DATABASE
FEATURE_DEFINES += ENABLE_INDEXED_DATABASE=1
webcore_cppflags += -DENABLE_INDEXED_DATABASE=1
endif # END ENABLE_INDEXED_DATABASE

if USE_LEVELDB
webcore_cppflags += -DWTF_USE_LEVELDB
endif # END USE_LEVELDB

# ----
# Support for <input type="file" directory>
# ----
if ENABLE_DIRECTORY_UPLOAD
FEATURE_DEFINES += ENABLE_DIRECTORY_UPLOAD=1
webcore_cppflags += -DENABLE_DIRECTORY_UPLOAD=1
else
webcore_cppflags += -DENABLE_DIRECTORY_UPLOAD=0
endif # END ENABLE_DIRECTORY_UPLOAD

# ----
# DOM mutation observer support
# ----
if ENABLE_MUTATION_OBSERVERS
FEATURE_DEFINES += ENABLE_MUTATION_OBSERVERS=1
webcore_cppflags += -DENABLE_MUTATION_OBSERVERS=1
endif # END ENABLE_MUTATION_OBSERVERS

# ----
# FileSystem API support
# ----
if ENABLE_FILE_SYSTEM
FEATURE_DEFINES += ENABLE_FILE_SYSTEM=1
webcore_cppflags += -DENABLE_FILE_SYSTEM=1
endif # END ENABLE_FILE_SYSTEM

# ----
# Quota support
# ----
if ENABLE_QUOTA
FEATURE_DEFINES += ENABLE_QUOTA=1
webcore_cppflags += -DENABLE_QUOTA=1
endif # END ENABLE_QUOTA

# ----
# Touch Icon Loading
# ----
if ENABLE_TOUCH_ICON_LOADING
FEATURE_DEFINES += ENABLE_TOUCH_ICON_LOADING=1
webcore_cppflags += -DENABLE_TOUCH_ICON_LOADING=1
else
webcore_cppflags += -DENABLE_TOUCH_ICON_LOADING=0
endif # END ENABLE_TOUCH_ICON_LOADING

# ----
# Color Input API support
# ----
if ENABLE_INPUT_TYPE_COLOR
FEATURE_DEFINES += ENABLE_INPUT_TYPE_COLOR=1
webcore_cppflags += -DENABLE_INPUT_TYPE_COLOR=1
else
webcore_cppflags += -DENABLE_INPUT_TYPE_COLOR=0
endif # END ENABLE_INPUT_TYPE_COLOR

# ----
# Speech Input API support
# ----
if ENABLE_INPUT_SPEECH
FEATURE_DEFINES += ENABLE_INPUT_SPEECH=1
webcore_cppflags += -DENABLE_INPUT_SPEECH=1
else
webcore_cppflags += -DENABLE_INPUT_SPEECH=0
endif # END ENABLE_INPUT_SPEECH

# ----
# Scripted Speech API support
# ----
if ENABLE_SCRIPTED_SPEECH
FEATURE_DEFINES += ENABLE_SCRIPTED_SPEECH=1
webcore_cppflags += -DENABLE_SCRIPTED_SPEECH=1
else
webcore_cppflags += -DENABLE_SCRIPTED_SPEECH=0
endif # END ENABLE_SCRIPTED_SPEECH

# ----
# Icon Database Support
# ----
if ENABLE_ICONDATABASE
webcore_cppflags += -DENABLE_ICONDATABASE=1
else
webcore_cppflags += -DENABLE_ICONDATABASE=0
endif # END ENABLE_ICONDATABASE

# ----
# Orientation Events
# ----
if ENABLE_ORIENTATION_EVENTS
FEATURE_DEFINES += ENABLE_ORIENTATION_EVENTS=1
webcore_cppflags += -DENABLE_ORIENTATION_EVENTS=1
endif # END ENABLE_ORIENTATION_EVENTS

# ----
# Video Support
# ----
if ENABLE_VIDEO
FEATURE_DEFINES += ENABLE_VIDEO=1
webcore_cppflags += -DENABLE_VIDEO=1

if USE_GSTREAMER
if ENABLE_DEBUG
webcore_cppflags += -DGST_DISABLE_DEPRECATED
endif # END ENABLE_DEBUG
endif # END USE_GSTREAMER
endif # END ENABLE_VIDEO

# ----
# Media Source Support
# ----
if ENABLE_MEDIA_SOURCE
FEATURE_DEFINES += ENABLE_MEDIA_SOURCE=1
webcore_cppflags += -DENABLE_MEDIA_SOURCE=1
else
webcore_cppflags += -DENABLE_MEDIA_SOURCE=0
endif # END ENABLE_MEDIA_SOURCE

# ----
# Media Statistics Support
# ----
if ENABLE_MEDIA_STATISTICS
FEATURE_DEFINES += ENABLE_MEDIA_STATISTICS=1
webcore_cppflags += -DENABLE_MEDIA_STATISTICS=1
else
webcore_cppflags += -DENABLE_MEDIA_STATISTICS=0
endif # END ENABLE_MEDIA_STATISTICS

# ----
# Javascript Fullscreen Support
# ----
if ENABLE_FULLSCREEN_API
FEATURE_DEFINES += ENABLE_FULLSCREEN_API=1
webcore_cppflags += -DENABLE_FULLSCREEN_API=1
endif # END ENABLE_FULLSCREEN_API

# ----
# Track Support
# ----
if ENABLE_VIDEO_TRACK
FEATURE_DEFINES += ENABLE_VIDEO_TRACK=1
webcore_cppflags += -DENABLE_VIDEO_TRACK=1
else
webcore_cppflags += -DENABLE_VIDEO_TRACK=0
endif # END ENABLE_VIDEO_TRACK

# ----
# Media Stream Support
# ----
if ENABLE_MEDIA_STREAM
FEATURE_DEFINES += ENABLE_MEDIA_STREAM=1
webcore_cppflags += -DENABLE_MEDIA_STREAM=1
else
webcore_cppflags += -DENABLE_MEDIA_STREAM=0
endif # END ENABLE_MEDIA_STREAM

# XPath grammar
# NOTE: older versions of bison do not inject an inclusion guard, so we do it
$(GENSOURCES_WEBCORE)/XPathGrammar.h: $(GENSOURCES_WEBCORE)/XPathGrammar.cpp
$(GENSOURCES_WEBCORE)/XPathGrammar.cpp: $(WebCore)/xml/XPathGrammar.y
	$(AM_V_GEN)
	$(AM_V_at)rm -f $(GENSOURCES_WEBCORE)/XPathGrammar.cpp.h $(GENSOURCES_WEBCORE)/XPathGrammar.hpp
	$(AM_V_at)$(BISON) -d -p xpathyy $< -o $(GENSOURCES_WEBCORE)/XPathGrammar.cpp
	$(AM_V_at)touch $(GENSOURCES_WEBCORE)/XPathGrammar.cpp.h $(GENSOURCES_WEBCORE)/XPathGrammar.hpp
	$(AM_V_at)echo '#ifndef XPathGrammar_h' > $(GENSOURCES_WEBCORE)/XPathGrammar.h
	$(AM_V_at)echo '#define XPathGrammar_h' >> $(GENSOURCES_WEBCORE)/XPathGrammar.h
	$(AM_V_at)cat $(GENSOURCES_WEBCORE)/XPathGrammar.cpp.h $(GENSOURCES_WEBCORE)/XPathGrammar.hpp >> $(GENSOURCES_WEBCORE)/XPathGrammar.h
	$(AM_V_at)echo '#endif' >> $(GENSOURCES_WEBCORE)/XPathGrammar.h
	$(AM_V_at)rm -f $(GENSOURCES_WEBCORE)/XPathGrammar.cpp.h $(GENSOURCES_WEBCORE)/XPathGrammar.hpp

# ----
# XSLT Support
# ----
if ENABLE_XSLT
FEATURE_DEFINES += ENABLE_XSLT=1
webcore_cppflags += -DENABLE_XSLT=1
endif # END ENABLE_XSLT

# ----
# Web Workers support
# ----
if ENABLE_WORKERS
FEATURE_DEFINES += ENABLE_WORKERS=1
webcore_cppflags += -DENABLE_WORKERS=1
endif

# ---
# Shadow DOM support
# ---
if ENABLE_SHADOW_DOM
FEATURE_DEFINES += ENABLE_SHADOW_DOM=1
webcore_cppflags += -DENABLE_SHADOW_DOM=1
endif

# ---
# SharedWorker support
# ---
if ENABLE_SHARED_WORKERS
FEATURE_DEFINES += ENABLE_SHARED_WORKERS=1
webcore_cppflags += -DENABLE_SHARED_WORKERS=1
endif

# ----
# Filters
# ----
if ENABLE_FILTERS
FEATURE_DEFINES += ENABLE_FILTERS=1
webcore_cppflags += -DENABLE_FILTERS=1
endif # END ENABLE_FILTERS

# ----
# CSS box decoration break
# ----
if ENABLE_CSS_BOX_DECORATION_BREAK
FEATURE_DEFINES += ENABLE_CSS_BOX_DECORATION_BREAK=1
webcore_cppflags += -DENABLE_CSS_BOX_DECORATION_BREAK=1

endif # END ENABLE_CSS_BOX_DECORATION_BREAK

# ----
# Regions
# ----
if ENABLE_CSS_REGIONS
FEATURE_DEFINES += ENABLE_CSS_REGIONS=1
webcore_cppflags += -DENABLE_CSS_REGIONS=1

endif # END ENABLE_CSS_REGIONS

# ----
# Filters
# ----
if ENABLE_CSS_FILTERS
FEATURE_DEFINES += ENABLE_CSS_FILTERS=1
webcore_cppflags += -DENABLE_CSS_FILTERS=1

endif # END ENABLE_CSS_FILTERS

# ----
# Compositing
# ----
if ENABLE_CSS_COMPOSITING
FEATURE_DEFINES += ENABLE_CSS_COMPOSITING=1
webcore_cppflags += -DENABLE_CSS_COMPOSITING=1
endif # END ENABLE_CSS_COMPOSITING

# ----
# Exclusions
# ----
if ENABLE_CSS_EXCLUSIONS
FEATURE_DEFINES += ENABLE_CSS_EXCLUSIONS=1
webcore_cppflags += -DENABLE_CSS_EXCLUSIONS=1

endif # END ENABLE_CSS_EXCLUSIONS

# ----
# Geolocation
# ----
if ENABLE_GEOLOCATION

FEATURE_DEFINES += ENABLE_GEOLOCATION=1
webcore_cppflags += -DENABLE_GEOLOCATION=1
endif # END ENABLE_GEOLOCATION

# ----
# MathML support
# ----
if ENABLE_MATHML
FEATURE_DEFINES += ENABLE_MATHML=1
webcore_cppflags += -DENABLE_MATHML=1
endif # END ENABLE_MATHML

# MathML tag and attribute names, and element factory
DerivedSources/WebCore/MathMLElementFactory.h: DerivedSources/WebCore/MathMLElementFactory.cpp
DerivedSources/WebCore/MathMLNames.h: DerivedSources/WebCore/MathMLNames.cpp
DerivedSources/WebCore/MathMLElementFactory.cpp DerivedSources/WebCore/MathMLNames.cpp: $(WebCore)/dom/make_names.pl $(WebCore)/mathml/mathtags.in $(WebCore)/mathml/mathattrs.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --tags $(WebCore)/mathml/mathtags.in --attrs $(WebCore)/mathml/mathattrs.in --factory --wrapperFactory --outputDir "$(GENSOURCES_WEBCORE)"

# ----
# Notifications support
# ----
if ENABLE_NOTIFICATIONS
FEATURE_DEFINES += ENABLE_NOTIFICATIONS=1 ENABLE_LEGACY_NOTIFICATIONS=1
webcore_cppflags += -DENABLE_NOTIFICATIONS=1 -DENABLE_LEGACY_NOTIFICATIONS=1
endif # END ENABLE_NOTIFICATIONS

# ----
# SVG Support
#
# FIXME: allow a more fine-grained inclusion/generation of sources per SVG feature
# ----
if ENABLE_SVG
nodist_libWebCoreSVG_la_SOURCES = \
       $(webcore_svg_built_sources)

libWebCoreSVG_la_SOURCES = \
       $(webcore_svg_sources)

libWebCoreSVG_la_CXXFLAGS = \
       $(SYMBOL_VISIBILITY_INLINES) \
       $(global_cxxflags)

libWebCoreSVG_la_CFLAGS = \
       $(SYMBOL_VISIBILITY) \
       $(global_cflags)

libWebCoreSVG_la_CPPFLAGS = \
       -DBUILDING_WebCore \
       -DBUILDING_WEBKIT \
       $(global_cppflags) \
       $(webcore_cppflags) \
       $(webcoregtk_cppflags) \
       $(javascriptcore_cppflags) \
       -fno-strict-aliasing \
       $(CAIRO_CFLAGS) \
       $(LIBSOUP_CFLAGS)

FEATURE_DEFINES += ENABLE_SVG=1
webcore_cppflags += -DENABLE_SVG=1
WEBCORE_CSS_PROPERTY_NAMES += $(WebCore)/css/SVGCSSPropertyNames.in
WEBCORE_CSS_VALUE_KEYWORDS += $(WebCore)/css/SVGCSSValueKeywords.in

# SVG Features
if ENABLE_SVG_FONTS
FEATURE_DEFINES += ENABLE_SVG_FONTS=1
webcore_cppflags += -DENABLE_SVG_FONTS=1
endif

endif # END ENABLE_SVG

# SVG tag and attribute names (need to pass an extra flag if svg experimental features are enabled)
DerivedSources/WebCore/SVGNames.cpp: DerivedSources/WebCore/SVGElementFactory.cpp
DerivedSources/WebCore/JSSVGElementWrapperFactory.cpp: DerivedSources/WebCore/SVGElementFactory.cpp
DerivedSources/WebCore/SVGElementFactory.cpp: $(WebCore)/dom/make_names.pl $(WebCore)/svg/svgtags.in $(WebCore)/svg/svgattrs.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --tags $(WebCore)/svg/svgtags.in --attrs $(WebCore)/svg/svgattrs.in --extraDefines "$(FEATURE_DEFINES)" --factory --wrapperFactory --outputDir "$(GENSOURCES_WEBCORE)"

# end SVG Features

DerivedSources/WebCore/XLinkNames.h: DerivedSources/WebCore/XLinkNames.cpp
DerivedSources/WebCore/XLinkNames.cpp : $(WebCore)/dom/make_names.pl $(WebCore)/svg/xlinkattrs.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --attrs $(WebCore)/svg/xlinkattrs.in --outputDir "$(GENSOURCES_WEBCORE)"

# ----
# Web Audio Support
# ----
if ENABLE_WEB_AUDIO
FEATURE_DEFINES += ENABLE_WEB_AUDIO=1
webcore_cppflags += -DENABLE_WEB_AUDIO=1
endif

if USE_WEBAUDIO_GSTREAMER
webcore_cppflags += -DWTF_USE_WEBAUDIO_GSTREAMER=1
endif

# ----
# Web Sockets Support
# ----
if ENABLE_WEB_SOCKETS
FEATURE_DEFINES += ENABLE_WEB_SOCKETS=1
webcore_cppflags += -DENABLE_WEB_SOCKETS=1
else
webcore_cppflags += -DENABLE_WEB_SOCKETS=0
endif  # END ENABLE_WEB_SOCKETS

# ---
# Blob support
# ---
if ENABLE_BLOB
FEATURE_DEFINES += ENABLE_BLOB=1
webcore_cppflags += -DENABLE_BLOB=1
endif  # END ENABLE_BLOB

# ---
# Legacy WebKitBlobBuilder support
# ---
if ENABLE_LEGACY_WEBKIT_BLOB_BUILDER
FEATURE_DEFINES += ENABLE_LEGACY_WEBKIT_BLOB_BUILDER=1
webcore_cppflags += -DENABLE_LEGACY_WEBKIT_BLOB_BUILDER=1
endif  # END ENABLE_LEGACY_WEBKIT_BLOB_BUILDER

# ---
# Animation API support
# ---
if ENABLE_ANIMATION_API
FEATURE_DEFINES += ENABLE_ANIMATION_API=1
webcore_cppflags += -DENABLE_ANIMATION_API=1
endif  # END ENABLE_ANIMATION_API

# ---
# RequestAnimationFrame support
# ---
if ENABLE_REQUEST_ANIMATION_FRAME
FEATURE_DEFINES += ENABLE_REQUEST_ANIMATION_FRAME=1
webcore_cppflags += -DENABLE_REQUEST_ANIMATION_FRAME=1
endif  # END ENABLE_REQUEST_ANIMATION_FRAME

# ---
# 3D canvas (WebGL) support
# ---
if ENABLE_WEBGL
FEATURE_DEFINES += ENABLE_WEBGL=1
webcore_cppflags += -DENABLE_WEBGL=1
endif  # END ENABLE_WEBGL

# ---
# Accelerated compositing support
# ---
if USE_ACCELERATED_COMPOSITING
FEATURE_DEFINES += \
	ENABLE_3D_RENDERING=1 \
	ACCELERATED_COMPOSITING=1
endif  # END USE_ACCELERATED_COMPOSITING

if USE_TEXTURE_MAPPER_CAIRO
webcore_cppflags += \
	-I$(srcdir)/Source/WebCore/platform/graphics/texmap
endif  # END USE_TEXTURE_MAPPER_CAIRO

if USE_TEXTURE_MAPPER_GL
webcore_cppflags += \
	-I$(srcdir)/Source/WebCore/platform/graphics/texmap
endif  # END USETEXTURE_MAPPER_GL

if USE_CLUTTER
webcore_cppflags += \
	-I$(srcdir)/Source/WebCore/platform/clutter \
	-I$(srcdir)/Source/WebCore/platform/graphics/clutter
endif  # END USE_CLUTTER

# ---
# MHTML support
# ---
if ENABLE_MHTML
FEATURE_DEFINES += ENABLE_MHTML=1
webcore_cppflags += \
	-DENABLE_MHTML=1 \
	-I$(srcdir)/Source/WebCore/loader/archive/mhtml
endif  # END ENABLE_MHTML

# ---
# HTML5 Microdata support
# ---
if ENABLE_MICRODATA
FEATURE_DEFINES += ENABLE_MICRODATA=1
webcore_cppflags += -DENABLE_MICRODATA=1
endif  # END ENABLE_MICRODATA

# ---
# Register Protocol Handler support
# ---
if ENABLE_REGISTER_PROTOCOL_HANDLER
FEATURE_DEFINES += ENABLE_REGISTER_PROTOCOL_HANDLER=1
webcore_cppflags += -DENABLE_REGISTER_PROTOCOL_HANDLER=1
endif  # END ENABLE_REGISTER_PROTOCOL_HANDLER

# ---
# DeviceOrientation support
# ---
if ENABLE_DEVICE_ORIENTATION
FEATURE_DEFINES += ENABLE_DEVICE_ORIENTATION=1
webcore_cppflags += -DENABLE_DEVICE_ORIENTATION=1
endif  # END ENABLE_DEVICE_ORIENTATION

# ---
# Text Autosizing support
# ---
if ENABLE_TEXT_AUTOSIZING
FEATURE_DEFINES += ENABLE_TEXT_AUTOSIZING=1
webcore_cppflags += -DENABLE_TEXT_AUTOSIZING=1
endif  # END ENABLE_TEXT_AUTOSIZING

# ---
# Web Timing support
# ---
if ENABLE_WEB_TIMING
FEATURE_DEFINES += ENABLE_WEB_TIMING=1
webcore_cppflags += -DENABLE_WEB_TIMING=1
endif  # END ENABLE_WEB_TIMING

# ---
# HTML iframe seamless attribute support
# ---
if ENABLE_IFRAME_SEAMLESS
FEATURE_DEFINES += ENABLE_IFRAME_SEAMLESS=1
webcore_cppflags += -DENABLE_IFRAME_SEAMLESS=1
endif  # END ENABLE_IFRAME_SEAMLESS

# ---
# CSS3 Flexbox support
# ---
if ENABLE_CSS3_FLEXBOX
FEATURE_DEFINES += ENABLE_CSS3_FLEXBOX=1
webcore_cppflags += -DENABLE_CSS3_FLEXBOX=1
endif  # END ENABLE_CSS3_FLEXBOX

# ---
# CSS3 Text Decoration support
if ENABLE_CSS3_TEXT_DECORATION
FEATURE_DEFINES += ENABLE_CSS3_TEXT_DECORATION=1
webcore_cppflags += -DENABLE_CSS3_TEXT_DECORATION=1
endif # END ENABLE_CSS3_TEXT_DECORATION

# ---
# Link prefetch support
# ---
if ENABLE_LINK_PREFETCH
FEATURE_DEFINES += ENABLE_LINK_PREFETCH=1
webcore_cppflags += -DENABLE_LINK_PREFETCH=1
endif  # END ENABLE_LINK_PREFETCH

# ---
# Widget region support
# ---
if ENABLE_WIDGET_REGION
FEATURE_DEFINES += ENABLE_WIDGET_REGION=1
webcore_cppflags += -DENABLE_WIDGET_REGION=1
endif  # END ENABLE_WIDGET_REGION

# ---
# Spell check support
# ---
if ENABLE_SPELLCHECK
FEATURE_DEFINES += ENABLE_SPELLCHECK=1
webcore_cppflags += -DENABLE_SPELLCHECK=1
endif  # END ENABLE_SPELLCHECK

DerivedSources/WebCore/CSSPropertyNames.cpp: DerivedSources/WebCore/CSSPropertyNames.h
DerivedSources/WebCore/CSSPropertyNames.h: $(WEBCORE_CSS_PROPERTY_NAMES) $(WebCore)/css/makeprop.pl
	$(AM_V_GEN)
	$(AM_V_at)cat $(WEBCORE_CSS_PROPERTY_NAMES) > CSSPropertyNames.in
	$(AM_V_at)$(PERL) -I$(WebCore)/bindings/scripts "$(WebCore)/css/makeprop.pl" --defines "$(FEATURE_DEFINES)"
	$(AM_V_at)mv CSSPropertyNames* $(GENSOURCES_WEBCORE)

# Lower case all the values, as CSS values are case-insensitive
DerivedSources/WebCore/CSSValueKeywords.cpp: DerivedSources/WebCore/CSSValueKeywords.h
DerivedSources/WebCore/CSSValueKeywords.h: $(WEBCORE_CSS_VALUE_KEYWORDS) $(WebCore)/css/makevalues.pl
	$(AM_V_GEN)
	$(AM_V_at)cat $(WEBCORE_CSS_VALUE_KEYWORDS) > CSSValueKeywords.in
	$(AM_V_at)$(PERL) -I$(WebCore)/bindings/scripts "$(WebCore)/css/makevalues.pl" --defines "$(FEATURE_DEFINES)"
	$(AM_V_at)mv CSSValueKeywords* $(GENSOURCES_WEBCORE)

# XML Viewer CSS
DerivedSources/WebCore/XMLViewerCSS.h: $(WebCore)/xml/XMLViewer.css
	$(AM_V_GEN)$(PERL) $(WebCore)/inspector/xxd.pl XMLViewer_css $(WebCore)/xml/XMLViewer.css $(GENSOURCES_WEBCORE)/XMLViewerCSS.h

# XML Viewer JS
DerivedSources/WebCore/XMLViewerJS.h: $(WebCore)/xml/XMLViewer.js
	$(AM_V_GEN)$(PERL) $(WebCore)/inspector/xxd.pl XMLViewer_js $(WebCore)/xml/XMLViewer.js $(GENSOURCES_WEBCORE)/XMLViewerJS.h

# HTML entity names
DerivedSources/WebCore/HTMLEntityTable.cpp: $(WebCore)/html/parser/HTMLEntityNames.in $(WebCore)/html/parser/create-html-entity-table
	$(AM_V_GEN)$(PYTHON) $(WebCore)/html/parser/create-html-entity-table -o $(GENSOURCES_WEBCORE)/HTMLEntityTable.cpp $(WebCore)/html/parser/HTMLEntityNames.in

# color names
DerivedSources/WebCore/ColorData.cpp: $(WebCore)/platform/ColorData.gperf $(WebCore)/make-hash-tools.pl
	$(AM_V_GEN)$(PERL) $(WebCore)/make-hash-tools.pl $(GENSOURCES_WEBCORE) $(WebCore)/platform/ColorData.gperf

# CSS grammar

# NOTE: older versions of bison do not inject an inclusion guard, so we do it
DerivedSources/WebCore/CSSGrammar.h: $(GENSOURCES_WEBCORE)/CSSGrammar.cpp
DerivedSources/WebCore/CSSGrammar.cpp: $(WebCore)/css/CSSGrammar.y
	$(AM_V_GEN)
	$(AM_V_at)rm -f $(GENSOURCES_WEBCORE)/CSSGrammar.cpp.h $(GENSOURCES_WEBCORE)/CSSGrammar.hpp
	$(AM_V_at)$(BISON) -d -p cssyy $< -o $(GENSOURCES_WEBCORE)/CSSGrammar.cpp
	$(AM_V_at)touch $(GENSOURCES_WEBCORE)/CSSGrammar.cpp.h $(GENSOURCES_WEBCORE)/CSSGrammar.hpp
	$(AM_V_at)echo '#ifndef CSSGrammar_h' > $(GENSOURCES_WEBCORE)/CSSGrammar.h
	$(AM_V_at)echo '#define CSSGrammar_h' >> $(GENSOURCES_WEBCORE)/CSSGrammar.h
	$(AM_V_at)cat $(GENSOURCES_WEBCORE)/CSSGrammar.cpp.h $(GENSOURCES_WEBCORE)/CSSGrammar.hpp >> $(GENSOURCES_WEBCORE)/CSSGrammar.h
	$(AM_V_at)echo '#endif' >> $(GENSOURCES_WEBCORE)/CSSGrammar.h
	$(AM_V_at)rm -f $(GENSOURCES_WEBCORE)/CSSGrammar.cpp.h $(GENSOURCES_WEBCORE)/CSSGrammar.hpp

# user agent style sheets
USER_AGENT_STYLE_SHEETS = \
	$(WebCore)/css/html.css \
	$(WebCore)/css/mathml.css \
	$(WebCore)/css/quirks.css \
	$(WebCore)/css/view-source.css \
	$(WebCore)/css/svg.css \
	$(WebCore)/css/mediaControls.css \
	$(WebCore)/css/mediaControlsGtk.css \
	$(WebCore)/css/fullscreen.css

# new-style JavaScript bindings
SCRIPTS_FOR_GENERATE_BINDINGS = \
	$(WebCore)/bindings/scripts/CodeGenerator.pm \
	$(WebCore)/bindings/scripts/IDLParser.pm \
	$(WebCore)/bindings/scripts/IDLStructure.pm \
	$(WebCore)/bindings/scripts/InFilesCompiler.pm \
	$(WebCore)/bindings/scripts/InFilesParser.pm \
	$(WebCore)/bindings/scripts/generate-bindings.pl \
	$(WebCore)/bindings/scripts/preprocessor.pm

SCRIPTS_FOR_PREPROCESS_IDLS = \
	$(WebCore)/bindings/scripts/IDLParser.pm \
	$(WebCore)/bindings/scripts/preprocess-idls.pl

DerivedSources/WebCore/UserAgentStyleSheetsData.cpp: DerivedSources/WebCore/UserAgentStyleSheets.h
DerivedSources/WebCore/UserAgentStyleSheets.h: $(WebCore)/css/make-css-file-arrays.pl $(WebCore)/bindings/scripts/preprocessor.pm $(USER_AGENT_STYLE_SHEETS)
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $<  --defines "$(FEATURE_DEFINES)" $@ DerivedSources/WebCore/UserAgentStyleSheetsData.cpp $(USER_AGENT_STYLE_SHEETS)

DerivedSources/WebCore/WebKitFontFamilyNames.cpp: DerivedSources/WebCore/WebKitFontFamilyNames.h
DerivedSources/WebCore/WebKitFontFamilyNames.h: $(WebCore)/dom/make_names.pl $(WebCore)/css/WebKitFontFamilyNames.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --fonts $(WebCore)/css/WebKitFontFamilyNames.in --outputDir "$(GENSOURCES_WEBCORE)"


# HTML tag and attribute names
DerivedSources/WebCore/JSHTMLElementWrapperFactory.cpp: DerivedSources/WebCore/HTMLElementFactory.cpp
DerivedSources/WebCore/HTMLElementFactory.cpp: DerivedSources/WebCore/HTMLElementFactory.h
DerivedSources/WebCore/HTMLElementFactory.h: DerivedSources/WebCore/HTMLNames.cpp
DerivedSources/WebCore/HTMLNames.cpp: DerivedSources/WebCore/HTMLNames.h
DerivedSources/WebCore/HTMLNames.h: $(WebCore)/dom/make_names.pl $(WebCore)/html/HTMLTagNames.in $(WebCore)/html/HTMLAttributeNames.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --tags $(WebCore)/html/HTMLTagNames.in --attrs $(WebCore)/html/HTMLAttributeNames.in --extraDefines "$(FEATURE_DEFINES)" --factory --wrapperFactory --outputDir "$(GENSOURCES_WEBCORE)"


DerivedSources/WebCore/XMLNSNames.cpp DerivedSources/WebCore/XMLNSNames.h: $(WebCore)/dom/make_names.pl $(WebCore)/xml/xmlnsattrs.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --attrs $(WebCore)/xml/xmlnsattrs.in --outputDir "$(GENSOURCES_WEBCORE)"

DerivedSources/WebCore/XMLNames.cpp DerivedSources/WebCore/XMLNames.h: $(WebCore)/dom/make_names.pl $(WebCore)/xml/xmlattrs.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --attrs $(WebCore)/xml/xmlattrs.in --outputDir "$(GENSOURCES_WEBCORE)"

DerivedSources/WebCore/EventFactory.cpp DerivedSources/WebCore/EventHeaders.h DerivedSources/WebCore/EventInterfaces.h: $(WebCore)/dom/make_event_factory.pl $(WebCore)/dom/EventNames.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --input $(WebCore)/dom/EventNames.in --outputDir "$(GENSOURCES_WEBCORE)"

DerivedSources/WebCore/EventTargetHeaders.h DerivedSources/WebCore/EventTargetInterfaces.h: $(WebCore)/dom/make_event_factory.pl $(WebCore)/dom/EventTargetFactory.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --input $(WebCore)/dom/EventTargetFactory.in --outputDir "$(GENSOURCES_WEBCORE)"

DerivedSources/WebCore/ExceptionCodeDescription.cpp DerivedSources/WebCore/ExceptionCodeDescription.h DerivedSources/WebCore/ExceptionHeaders.h DerivedSources/WebCore/ExceptionInterfaces.h: $(WebCore)/dom/make_dom_exceptions.pl $(WebCore)/dom/DOMExceptions.in
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $< --input $(WebCore)/dom/DOMExceptions.in --outputDir "$(GENSOURCES_WEBCORE)"

# All Web Inspector generated files are created with this one call to CodeGeneratorInspector.py
DerivedSources/WebCore/InspectorProtocolVersion.h : $(WebCore)/inspector/Inspector.json $(WebCore)/inspector/generate-inspector-protocol-version
	$(AM_V_GEN)$(PYTHON) $(WebCore)/inspector/generate-inspector-protocol-version -o $(GENSOURCES_WEBCORE)/InspectorProtocolVersion.h $(WebCore)/inspector/Inspector.json

DerivedSources/WebCore/InspectorBackendDispatcher.cpp: $(WebCore)/inspector/Inspector.json $(WebCore)/inspector/CodeGeneratorInspector.py
	$(AM_V_GEN)$(PYTHON) $(WebCore)/inspector/CodeGeneratorInspector.py $< --output_h_dir $(GENSOURCES_WEBCORE) --output_cpp_dir $(GENSOURCES_WEBCORE)
DerivedSources/WebCore/InspectorTypeBuilder.h: DerivedSources/WebCore/InspectorTypeBuilder.cpp
DerivedSources/WebCore/InspectorTypeBuilder.cpp: DerivedSources/WebCore/InspectorFrontend.h
DerivedSources/WebCore/InspectorFrontend.h: DerivedSources/WebCore/InspectorFrontend.cpp
DerivedSources/WebCore/InspectorFrontend.cpp: DerivedSources/WebCore/InspectorBackendCommands.js
DerivedSources/WebCore/InspectorBackendCommands.js: DerivedSources/WebCore/InspectorBackendDispatcher.h
DerivedSources/WebCore/InspectorBackendDispatcher.h: DerivedSources/WebCore/InspectorBackendDispatcher.cpp
DerivedSources/WebCore/InjectedScriptSource.h: $(WebCore)/inspector/InjectedScriptSource.js
	$(AM_V_GEN)$(PERL) $(WebCore)/inspector/xxd.pl InjectedScriptSource_js $(WebCore)/inspector/InjectedScriptSource.js $(GENSOURCES_WEBCORE)/InjectedScriptSource.h
DerivedSources/WebCore/InjectedScriptWebGLModuleSource.h: $(WebCore)/inspector/InjectedScriptWebGLModuleSource.js
	$(AM_V_GEN)$(PERL) $(WebCore)/inspector/xxd.pl InjectedScriptWebGLModuleSource_js $(WebCore)/inspector/InjectedScriptWebGLModuleSource.js $(GENSOURCES_WEBCORE)/InjectedScriptWebGLModuleSource.h

if ENABLE_WEB_AUDIO
# Installing HRTF database wav files
audiodir = ${datadir}/webkitgtk-@WEBKITGTK_API_VERSION@/resources/audio/
audio_DATA = $(WebCore)/platform/audio/resources/Composite.wav
dist_audio_DATA = $(audio_DATA)
endif  # END ENABLE_WEB_AUDIO

# ANGLE tokenizer & parser
DerivedSources/ANGLE/glslang.cpp: Source/ThirdParty/ANGLE/src/compiler/glslang.l
	$(AM_V_GEN)$(FLEX) --noline --nounistd --outfile="$@" "$<"

DerivedSources/ANGLE/glslang_tab.cpp: Source/ThirdParty/ANGLE/src/compiler/glslang.y
	$(AM_V_GEN)$(BISON) --no-lines --defines="DerivedSources/ANGLE/glslang_tab.h" --skeleton=yacc.c --output="$@" $<
DerivedSources/ANGLE/glslang_tab.h: DerivedSources/ANGLE/glslang_tab.cpp

IDL_PATH := \
    $(WebCore)/Modules/filesystem \
    $(WebCore)/Modules/gamepad \
    $(WebCore)/Modules/geolocation \
    $(WebCore)/Modules/indexeddb \
    $(WebCore)/Modules/mediasource \
    $(WebCore)/Modules/mediastream \
    $(WebCore)/Modules/notifications \
    $(WebCore)/Modules/quota \
    $(WebCore)/Modules/webaudio \
    $(WebCore)/Modules/webdatabase \
    $(WebCore)/Modules/websockets \
    $(WebCore)/bindings/js \
    $(WebCore)/css \
    $(WebCore)/dom \
    $(WebCore)/editing \
    $(WebCore)/fileapi \
    $(WebCore)/html \
    $(WebCore)/html/canvas \
    $(WebCore)/html/shadow \
    $(WebCore)/html/track \
    $(WebCore)/inspector \
    $(WebCore)/loader/appcache \
    $(WebCore)/page \
    $(WebCore)/plugins \
    $(WebCore)/storage \
    $(WebCore)/svg \
    $(WebCore)/testing \
    $(WebCore)/workers \
    $(WebCore)/xml

vpath %.idl $(IDL_PATH)

supplemental_dependency_file = $(top_builddir)/DerivedSources/WebCore/idl_supplemental_dependencies
idl_files_list = $(top_builddir)/DerivedSources/WebCore/idl_files_list
idl_attributes_file = $(WebCore)/bindings/scripts/IDLAttributes.txt

.SECONDARY:
$(supplemental_dependency_file): $(SCRIPTS_FOR_PREPROCESS_IDLS) $(dom_binding_idls) $(idl_attributes_file)
	$(AM_V_GEN)
	$(AM_V_at)echo -n > $(idl_files_list)
	$(AM_V_at)($(foreach idl, $(dom_binding_idls), echo $(idl) &&) echo -n) >> $(idl_files_list)
	$(AM_V_at)$(PERL) -I$(WebCore)/bindings/scripts $(WebCore)/bindings/scripts/preprocess-idls.pl --defines "LANGUAGE_JAVASCRIPT=1 $(FEATURE_DEFINES)" --idlFilesList $(idl_files_list) --supplementalDependencyFile $@ --idlAttributesFile $(idl_attributes_file)

# This does not appear to work correctly with gnumake unless
# it includes an empty command list (the semicolon).
DerivedSources/WebCore/JS%.cpp: DerivedSources/WebCore/JS%.h;

.SECONDARY:
DerivedSources/WebCore/JS%.h: %.idl $(SCRIPTS_FOR_GENERATE_BINDINGS) $(WebCore)/bindings/scripts/CodeGeneratorJS.pm $(supplemental_dependency_file)
	$(AM_V_GEN)$(PERL) -I$(WebCore)/bindings/scripts $(WebCore)/bindings/scripts/generate-bindings.pl $(IDL_PATH:%=--include "%") --outputDir "$(GENSOURCES_WEBCORE)" --defines "LANGUAGE_JAVASCRIPT=1 $(FEATURE_DEFINES)" --generator JS --supplementalDependencyFile $(supplemental_dependency_file) $<

# See https://bugs.webkit.org/show_bug.cgi?id=76388
# We need to introduce a manual dependency to prevent non-generated sources from
# trying to build before the generated ones. This can happen if the supplemental
# IDL generation takes a long time. The pipe represents an order-only dependency,
# which means that GNUmake will only try to build the dependencies first, but
# not rebuild all the targets if the dependencies change.
$(webkitgtk_sources) $(webkit2_sources) $(webkit2_plugin_process_sources) $(webcore_sources) $(webcoregtk_sources) : | $(supplemental_dependency_file) $(webcore_built_sources)

noinst_LTLIBRARIES += \
	libWebCorePlatform.la \
	libWebCoreModules.la \
	libWebCore.la

if ENABLE_SVG
noinst_LTLIBRARIES += \
       libWebCoreSVG.la
endif

# Artificial dependency to try to force a relink of the WebCore libraries
# When their makefiles change.
webcore_lib_for_dep = libWebCore.la
$(webcore_lib_for_dep): $(srcdir)/Source/WebCore/GNUmakefile.am $(srcdir)/Source/WebCore/GNUmakefile.list.am

webcoremodules_lib_for_dep = libWebcoreModules.la
$(webcoremodules_lib_for_dep): $(srcdir)/Source/WebCore/GNUmakefile.am $(srcdir)/Source/WebCore/GNUmakefile.list.am

webcoreplatform_lib_for_dep = libWebcorePlatform.la
$(webcoreplatform_lib_for_dep): $(srcdir)/Source/WebCore/GNUmakefile.am $(srcdir)/Source/WebCore/GNUmakefile.list.am

webcoresvg_lib_for_dep = libWebCoreSVG.la
$(webcoresvg_lib_for_dep): $(srcdir)/Source/WebCore/GNUmakefile.am $(srcdir)/Source/WebCore/GNUmakefile.list.am

nodist_EXTRA_libWebCore_la_SOURCES = \
       $(webcore_built_nosources)

nodist_libWebCore_la_SOURCES = \
       $(webcore_built_sources)

libWebCore_la_SOURCES = \
       $(webcore_sources)

libWebCore_la_CXXFLAGS = \
       $(SYMBOL_VISIBILITY_INLINES) \
       $(global_cxxflags)

libWebCore_la_CFLAGS = \
       $(SYMBOL_VISIBILITY) \
       $(global_cflags)

libWebCore_la_CPPFLAGS = \
	-DBUILDING_WebCore \
	-DBUILDING_WEBKIT \
	$(global_cppflags) \
	$(webcore_cppflags) \
	$(webcoregtk_cppflags) \
	$(javascriptcore_cppflags) \
	-fno-strict-aliasing \
	$(CAIRO_CFLAGS) \
	$(CLUTTER_CFLAGS) \
	$(COVERAGE_CFLAGS) \
	$(ENCHANT_CFLAGS) \
	$(GAMEPAD_CFLAGS) \
	$(GEOCLUE_CFLAGS) \
	$(GLIB_CFLAGS) \
	$(GSTREAMER_CFLAGS) \
	$(LIBSECRET_CFLAGS) \
	$(LIBSOUP_CFLAGS) \
	$(LIBXML_CFLAGS) \
	$(LIBXSLT_CFLAGS) \
	$(PANGO_CFLAGS) \
	$(SQLITE3_CFLAGS) \
	$(UNICODE_CFLAGS) \
	$(XRENDER_CFLAGS) \
	$(XT_CFLAGS)

if TARGET_WIN32
# PluginPackageWin.cpp needs the symbols from version dll
libWebCore_la_LIBADD = -lversion
endif

libWebCoreModules_la_SOURCES = \
	$(webcore_modules_sources)

libWebCoreModules_la_CXXFLAGS = $(libWebCore_la_CXXFLAGS)

libWebCoreModules_la_CFLAGS = $(libWebCore_la_CFLAGS)

libWebCoreModules_la_CPPFLAGS = $(libWebCore_la_CPPFLAGS)

libWebCorePlatform_la_SOURCES = \
	$(webcore_platform_sources)

libWebCorePlatform_la_CXXFLAGS = \
	$(SYMBOL_VISIBILITY_INLINES) \
	$(global_cxxflags)

libWebCorePlatform_la_CFLAGS = \
	$(SYMBOL_VISIBILITY) \
	$(global_cflags)

libWebCorePlatform_la_CPPFLAGS = \
	-DBUILDING_WEBKIT \
	$(global_cppflags) \
	$(webcore_cppflags) \
	$(webcoregtk_cppflags) \
	$(javascriptcore_cppflags) \
	-fno-strict-aliasing \
	$(CAIRO_CFLAGS) \
	$(CLUTTER_CFLAGS) \
	$(COVERAGE_CFLAGS) \
	$(ENCHANT_CFLAGS) \
	$(GAMEPAD_CFLAGS) \
	$(GEOCLUE_CFLAGS) \
	$(GLIB_CFLAGS) \
	$(GSTREAMER_CFLAGS) \
	$(LIBSECRET_CFLAGS) \
	$(LIBSOUP_CFLAGS) \
	$(LIBXML_CFLAGS) \
	$(LIBXSLT_CFLAGS) \
	$(PANGO_CFLAGS) \
	$(SQLITE3_CFLAGS) \
	$(UNICODE_CFLAGS) \
	$(XRENDER_CFLAGS) \
	$(XT_CFLAGS)

# We have a different library with only the files that require GTK+. It allows us
# to build a common WebCore lib and two different gtk WebCore libs depending on
# the gtk version. In WeKit2 gtk2 is not supported, but the plugin process needs to
# be built using gtk2 because plugins like flash still use gtk2. For WebKit2, we build
# the common libWebCore and two libWebCoreGtk, one using gtk3 and the other one using gtk2.
noinst_LTLIBRARIES += \
	libWebCoreGtk.la

libWebCoreGtk_la_SOURCES = \
	$(webcoregtk_sources)

libWebCoreGtk_la_CXXFLAGS = \
	$(SYMBOL_VISIBILITY_INLINES) \
	$(global_cxxflags)

libWebCoreGtk_la_CFLAGS = \
	$(SYMBOL_VISIBILITY) \
	$(global_cflags)

libWebCoreGtk_la_CPPFLAGS = \
	-DBUILDING_WebCore \
	-DBUILDING_WEBKIT \
	$(global_cppflags) \
	$(webcore_cppflags) \
	$(webcoregtk_cppflags) \
	$(javascriptcore_cppflags) \
	-fno-strict-aliasing \
	$(HILDON_CPPFLAGS) \
	$(CAIRO_CFLAGS) \
	$(CLUTTER_CFLAGS) \
	$(COVERAGE_CFLAGS) \
	$(ENCHANT_CFLAGS) \
	$(FARSTREAM_CFLAGS) \
	$(GAIL_CFLAGS) \
	$(GAMEPAD_CFLAGS) \
	$(GEOCLUE_CFLAGS) \
	$(GLIB_CFLAGS) \
	$(GSTREAMER_CFLAGS) \
	$(GTK_CFLAGS) \
	$(HILDON_CFLAGS) \
	$(LIBSECRET_CFLAGS) \
	$(LIBSOUP_CFLAGS) \
	$(LIBXML_CFLAGS) \
	$(LIBXSLT_CFLAGS) \
	$(SQLITE3_CFLAGS) \
	$(UNICODE_CFLAGS) \
	$(XCOMPOSITE_CFLAGS) \
	$(XDAMAGE_CFLAGS) \
	$(XRENDER_CFLAGS) \
	$(XT_CFLAGS)

EXTRA_DIST += \
	$(shell ls $(srcdir)/Source/WebCore/Modules/filesystem/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/gamepad/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/geolocation/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/indexeddb/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/mediasource/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/mediastream/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/notifications/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/protocolhandler/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/quota/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/webaudio/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/webdatabase/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/Modules/websockets/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/css/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/dom/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/editing/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/fileapi/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/html/canvas/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/html/shadow/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/html/track/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/html/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/inspector/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/loader/appcache/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/page/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/plugins/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/storage/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/svg/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/testing/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/workers/*.idl) \
	$(shell ls $(srcdir)/Source/WebCore/xml/*.idl) \
	Source/ThirdParty/ANGLE/src/compiler/glslang.l \
	Source/ThirdParty/ANGLE/src/compiler/glslang.y \
	Source/WebCore/bindings/scripts/CodeGeneratorGObject.pm \
	Source/WebCore/bindings/scripts/CodeGeneratorJS.pm \
	Source/WebCore/bindings/scripts/CodeGenerator.pm \
	Source/WebCore/bindings/scripts/IDLAttributes.txt \
	Source/WebCore/bindings/scripts/IDLParser.pm \
	Source/WebCore/bindings/scripts/IDLStructure.pm \
	Source/WebCore/bindings/scripts/InFilesCompiler.pm \
	Source/WebCore/bindings/scripts/InFilesParser.pm \
	Source/WebCore/bindings/scripts/generate-bindings.pl \
	Source/WebCore/bindings/scripts/gobject-generate-headers.pl \
	Source/WebCore/bindings/scripts/preprocessor.pm \
	Source/WebCore/bindings/scripts/preprocess-idls.pl \
	Source/WebCore/ChangeLog \
	Source/WebCore/css/CSSGrammar.y \
	Source/WebCore/css/CSSPropertyNames.in \
	Source/WebCore/css/CSSValueKeywords.in \
	Source/WebCore/dom/DOMExceptions.in \
	Source/WebCore/css/fullscreen.css \
	Source/WebCore/css/fullscreenQuickTime.css \
	Source/WebCore/css/html.css \
	Source/WebCore/css/make-css-file-arrays.pl \
	Source/WebCore/css/makegrammar.pl \
	Source/WebCore/css/makeprop.pl \
	Source/WebCore/css/maketokenizer \
	Source/WebCore/css/makevalues.pl \
	Source/WebCore/css/mathml.css \
	Source/WebCore/css/mediaControls.css \
	Source/WebCore/css/mediaControlsGtk.css \
	Source/WebCore/css/quirks.css \
	Source/WebCore/css/svg.css \
	Source/WebCore/css/SVGCSSPropertyNames.in \
	Source/WebCore/css/SVGCSSValueKeywords.in \
	Source/WebCore/css/view-source.css \
	Source/WebCore/css/WebKitFontFamilyNames.in \
	Source/WebCore/dom/EventNames.in \
	Source/WebCore/dom/EventTargetFactory.in \
	Source/WebCore/dom/make_dom_exceptions.pl \
	Source/WebCore/dom/make_event_factory.pl \
	Source/WebCore/dom/make_names.pl \
	Source/WebCore/html/HTMLAttributeNames.in \
	Source/WebCore/html/HTMLTagNames.in \
	Source/WebCore/html/parser/create-html-entity-table \
	Source/WebCore/html/parser/HTMLEntityNames.in \
	Source/WebCore/icu/LICENSE \
	Source/WebCore/inspector/CodeGeneratorInspector.py \
	Source/WebCore/inspector/InjectedScriptSource.js \
	Source/WebCore/inspector/InjectedScriptWebGLModuleSource.js \
	Source/WebCore/inspector/Inspector.json \
	Source/WebCore/inspector/Inspector-1.0.json \
	Source/WebCore/inspector/generate-inspector-protocol-version \
	Source/WebCore/inspector/xxd.pl \
	Source/WebCore/LICENSE-APPLE \
	Source/WebCore/LICENSE-LGPL-2 \
	Source/WebCore/LICENSE-LGPL-2.1 \
	Source/WebCore/make-hash-tools.pl \
	Source/WebCore/mathml/mathattrs.in \
	Source/WebCore/mathml/mathtags.in \
	Source/WebCore/platform/ColorData.gperf \
	Source/WebCore/platform/text/mac/make-charset-table.pl \
	Source/WebCore/svg/svgattrs.in \
	Source/WebCore/svg/svgtags.in \
	Source/WebCore/svg/xlinkattrs.in \
	Source/WebCore/xml/xmlattrs.in \
	Source/WebCore/xml/xmlnsattrs.in \
	Source/WebCore/xml/XMLViewer.css \
	Source/WebCore/xml/XMLViewer.js \
	Source/WebCore/xml/XPathGrammar.y

# Installing web inspector files
webinspectordir = ${datadir}/webkitgtk-@WEBKITGTK_API_VERSION@/webinspector
dist_webinspector_DATA = \
	$(WebCore)/English.lproj/localizedStrings.js \
	DerivedSources/WebCore/InspectorBackendCommands.js \
	$(shell ls $(WebCore)/inspector/front-end/*.js) \
	$(shell ls $(WebCore)/inspector/front-end/*.html) \
	$(shell ls $(WebCore)/inspector/front-end/*.css)

webinspectoruglifyjsdir = ${datadir}/webkitgtk-@WEBKITGTK_API_VERSION@/webinspector/UglifyJS
dist_webinspectoruglifyjs_DATA = \
	$(shell ls $(WebCore)/inspector/front-end/UglifyJS/*.js)

webinspectorimagesdir = ${datadir}/webkitgtk-@WEBKITGTK_API_VERSION@/webinspector/Images
dist_webinspectorimages_DATA = \
	$(shell ls $(WebCore)/inspector/front-end/Images/*.gif) \
	$(shell ls $(WebCore)/inspector/front-end/Images/*.png)

# It seems that $(shell) does not expand when it is a rule dependency, so
# we must redefine this list of copied files with traditional dependency wildcards.
noinst_DATA = ${GENSOURCES_INSPECTOR}/inspector.html
${GENSOURCES_INSPECTOR}/inspector.html: $(WebCore)/inspector/front-end/*.html \
		$(WebCore)/inspector/front-end/*.js \
		$(WebCore)/inspector/front-end/UglifyJS/*.js \
		$(WebCore)/inspector/front-end/*.css \
		$(WebCore)/inspector/front-end/Images/* \
		DerivedSources/WebCore/InspectorBackendCommands.js \
		$(WebCore)/English.lproj/localizedStrings.js
	$(AM_V_GEN)
	$(AM_V_at)mkdir -p ${GENSOURCES_INSPECTOR}/UglifyJS
	$(AM_V_at)mkdir -p ${GENSOURCES_INSPECTOR}/Images
	$(AM_V_at)cp ${dist_webinspector_DATA} ${GENSOURCES_INSPECTOR}
	$(AM_V_at)cp ${dist_webinspectoruglifyjs_DATA} ${GENSOURCES_INSPECTOR}/UglifyJS
	$(AM_V_at)cp ${dist_webinspectorimages_DATA} ${GENSOURCES_INSPECTOR}/Images

webresourcesdir = ${datadir}/webkitgtk-@WEBKITGTK_API_VERSION@/images
dist_webresources_DATA = \
	$(WebCore)/Resources/textAreaResizeCorner.png \
	$(WebCore)/Resources/nullPlugin.png \
	$(WebCore)/Resources/urlIcon.png \
	$(WebCore)/Resources/missingImage.png \
	$(WebCore)/Resources/panIcon.png \
	$(WebCore)/Resources/deleteButton.png \
	$(WebCore)/Resources/inputSpeech.png
