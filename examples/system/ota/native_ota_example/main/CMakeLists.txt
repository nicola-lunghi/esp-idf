set(COMPONENT_SRCS "native_ota_example.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")


# Embed the server root certificate into the final binary
#
# (If this was a component, we would set COMPONENT_EMBED_TXTFILES here.)
set(COMPONENT_EMBED_TXTFILES ../../server_certs/ca_cert.pem)

register_component()
