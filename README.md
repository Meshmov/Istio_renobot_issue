# Istio_renobot_issue

Whenever renovatebot detects packages for `istio.io/istio` the log shows -> `Failed to look up go dependency` 



in my go.mod:

`require istio.io/istio v0.0.0-20221208194603-fc52de67ee0e`

`require (
	istio.io/pkg v0.0.0-20230119194614-e877df450e1b // indirect
)`


in my go.sum:

`istio.io/istio v0.0.0-20221208194603-fc52de67ee0e 
istio.io/istio v0.0.0-20221208194603-fc52de67ee0e/go.mod 
istio.io/pkg v0.0.0-20230119194614-e877df450e1b 
istio.io/pkg v0.0.0-20230119194614-e877df450e1b/go.mod `
