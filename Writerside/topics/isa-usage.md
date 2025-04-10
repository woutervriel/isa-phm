# ISA Usage
ISA can be implemented via different tools. These tools rely on data exchange in one or two exchange formats: ISA-Tab and ISA-JSON.

## Data registration

The ISA <a href="https://isa-specs.readthedocs.io/en/latest/implementations.html" target="_blank">supporting software documentation</a> list the following table.

Multiple options are available for registering data according to the ISA data model. This project used the <a href="https://github.com/ISA-tools/isa-api" target="_blank">ISA Python API</a>.

| Tool                          | Description                                                                                                                                                | Format            | Development Status        | Platform                   |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|---------------------------|----------------------------|
| ISA API                       | Python API for ISA conversions, validation and content creation                                                                                            | ISA-Tab, ISA-JSON | Active (pre-release)      | Python 3+                  |
| ISA Explorer                  | Visualization and search over collections of ISA-Tabs (browser)                                                                                            | ISA-Tab, ISA-JSON | Not released -see preview | Python 3+                  |
| linkedISA                     | Convert ISA-Tab to OWL                                                                                                                                     | ISA-Tab           | Active                    | Java 1.6                   |
| OntoMaton                     | Annotation of ISA-Tab spreadsheets                                                                                                                         | ISA-Tab           | Active                    | Google Spreadsheets Add-on |
| rISA                          | Parse ISA-Tab into R data structures                                                                                                                       | ISA-Tab           | Active                    | R/Bioconductor             |
| biopy-isatab                  | Python Parser for ISA-Tab                                                                                                                                  | ISA-Tab           | Active                    | Python 2.7+                |
| ISA creator                   | Used for creating ISA-Tab files                                                                                                                            | ISA-Tab           | Maintenance mode          | Java 1.6                   |
| ISA-Tab Viewer                | Visualizer for ISA-Tabs (browser)                                                                                                                          | ISA-Tab           | Maintenance mode          | JavaScript / HTML / CSS    |
| ISA configurator              | Used with ISAcreator to develop ISA-Tab XML Configurations that are used as ISA-Tab templates and used for validating against domain-specific requirements | ISA-Tab           | Maintenance mode          | Java 1.6                   |
| ISA validator                 | Used with ISA XML Configurations to validate ISA-Tab files against domain-specific requirements                                                            | ISA-Tab           | Maintenance mode          | Java 1.6                   |
| ISA converter                 | Convert ISA-Tab files into other formats                                                                                                                   | ISA-Tab           | Maintenance mode          | Java 1.6                   |
| BII (Bio Investigation Index) | Web application and DB                                                                                                                                     | ISA-Tab           | Maintenance mode          | Java 1.6                   |
| MAGE to ISA converter         | Converter which can pull from ArrayExpress (by an accession number) or read local files and convert them to ISAtab.                                        | ISA-Tab           | Unsupported               | Java 1.6                   |


## Data Exchange formats
Data that is registered by using the ISA data model is stored and exchanged by either ISA-Tab or ISA-JSON. 

ISA-Tab is a collection of tab-delimited text files for the investigation, studies and assays. ISA-JSON is standard <a href="https://en.wikipedia.org/wiki/JSON" target="_blank">JSON</a> serialisation of the registered data, following the ISA data model.

