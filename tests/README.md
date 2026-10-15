# Network regression tests

Compile NetworkTests.cs together with source/Bridge.cs, source/Models.cs and source/NetworkErrors.cs, referencing System.Security.dll and the .NET 4.5 build of Newtonsoft.Json 13.0.3. Do not run the standalone test with the Unity/netstandard Newtonsoft.Json build.

Run the test executable without arguments for loopback HTTP fault injection and TLS/error classification checks. Pass `live` for an actual QR generation/poll request against the official KuGou endpoint. No account is required; temporary device data is written to test-account beside the executable. The test never scans or prints a QR/login token. Keep this folder out of version control.
