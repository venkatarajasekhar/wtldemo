project(QPreview)

set(src
	ImageInfo.cpp
	ImageInfo.h
	MemoryDC.h
	QPreview.cpp
	QPreview.h
	QPreview.rc
	SingleInst.cpp
	SingleInst.h
	WndPreview.cpp
	WndPreview.h
	XButton.cpp
	XButton.h
	resource.h
	stdafx.cpp
	stdafx.h

)

add_executable(QPreview ${src})