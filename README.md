# VSWithGPU

Pre requisites: Visual Studio integrated with Colab(google), Jupyter extensions

Script: This script verifies for ollama, 
	install_ollama():
		1) if ollama does not exists, it will install ollama on drive(google).
	   	   else if ollama exists in drive, it will ignore
	start_ollama_server():
		2) Run the ollama Server
	install_model():
		3) Server pulls the given model and installs on  drive(google) if model does not exist.
	   	   else it model exists in drive it wll ignore
	run_research_query(<query>):
		4) send query to receive reply
