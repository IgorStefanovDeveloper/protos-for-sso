<h1>Autogenerate GO code for sso service</h1>

<p>Generate GOlang files</p>
<code>protoc -I proto proto/sso/sso.proto --go_out=./gen/go --go_opt=paths=source_relative --go-grpc_out=./gen/go/ --go-grpc_opt=paths=source_relative</code>
