include Common/CommonDefs.mak

.PHONY: all

NETPROJ = 
ifneq "$(realpath /usr/bin/gmcs)" ""
endif

all: $(NETPROJ) NiHandTracker NiViewer NiRecordSynthetic NiAudioSample NiBackRecorder NiSimpleRead NiConvertXToONI NiSampleModule NiSkeletonBenchmark UserTracker.java NiUserSelection NiSimpleCreate NiSimpleViewer SimpleRead.java NiUserTracker NiCRead SimpleViewer.java NiSimpleSkeleton 


.PHONY: NiHandTracker
NiHandTracker:
	$(MAKE) -C ../NiHandTracker

.PHONY: NiViewer
NiViewer:
	$(MAKE) -C ../NiViewer

.PHONY: NiRecordSynthetic
NiRecordSynthetic:
	$(MAKE) -C ../NiRecordSynthetic

.PHONY: NiAudioSample
NiAudioSample:
	$(MAKE) -C ../NiAudioSample

.PHONY: NiBackRecorder
NiBackRecorder:
	$(MAKE) -C ../NiBackRecorder

.PHONY: NiSimpleRead
NiSimpleRead:
	$(MAKE) -C ../NiSimpleRead

.PHONY: NiConvertXToONI
NiConvertXToONI:
	$(MAKE) -C ../NiConvertXToONI

.PHONY: NiSampleModule
NiSampleModule:
	$(MAKE) -C ../NiSampleModule

.PHONY: NiSkeletonBenchmark
NiSkeletonBenchmark:
	$(MAKE) -C ../NiSkeletonBenchmark

.PHONY: UserTracker.java
UserTracker.java:
	$(MAKE) -C ../UserTracker.java

.PHONY: NiUserSelection
NiUserSelection:
	$(MAKE) -C ../NiUserSelection

.PHONY: NiSimpleCreate
NiSimpleCreate:
	$(MAKE) -C ../NiSimpleCreate

.PHONY: NiSimpleViewer
NiSimpleViewer:
	$(MAKE) -C ../NiSimpleViewer

.PHONY: SimpleRead.java
SimpleRead.java:
	$(MAKE) -C ../SimpleRead.java

.PHONY: NiUserTracker
NiUserTracker:
	$(MAKE) -C ../NiUserTracker

.PHONY: NiCRead
NiCRead:
	$(MAKE) -C ../NiCRead

.PHONY: SimpleViewer.java
SimpleViewer.java:
	$(MAKE) -C ../SimpleViewer.java

.PHONY: NiSimpleSkeleton
NiSimpleSkeleton:
	$(MAKE) -C ../NiSimpleSkeleton
