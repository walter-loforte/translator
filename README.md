# translator

Execute with java -jar translate-0.0.1-SNAPSHOT.jar apiKey language path_to_json_file

apiKey: Microsoft Translate Api Key

language: select language to translate to in the following format ("en" for English, "it" for Italian, etc..). It accepts comma separated values to translate to more than one language (i.e: en,it)

path_to_json_file: path to file with text to translate (there is one template in the project), it must have the provided json format in order to work.

*sample command line execution: 

* java -jar translate-0.0.1-SNAPSHOT.jar 123456fse1354 en path_to_json_file E:\\body.json
