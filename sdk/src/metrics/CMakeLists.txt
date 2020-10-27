add_library(opentelemetry_metrics meter_provider.cc meter.cc
                                  ungrouped_processor.cc)

install (TARGETS opentelemetry_metrics
		 ARCHIVE DESTINATION lib
		 LIBRARY DESTINATION lib
		 RUNTIME DESTINATION bin)