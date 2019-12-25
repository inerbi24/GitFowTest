add_executable(HelloWorld "")

target_sources(HelloWorld
	PRIVATE
		main.cpp
)

install(
	TARGETS HelloWorld
)