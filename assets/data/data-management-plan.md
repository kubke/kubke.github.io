# Data Management Plan

Project: Development of cranial nerve components in the chicken embryo.

## Contributors and Time Period

Period of time over which data will be generated: 24/07/17 - 01/11/18. This includes three periods during which the one overall project will be carried out. The three periods are: 
  1. “Scischol 302 Research Experience” project (24/07/17 – 02/11/17),
  2. “Summer Research Scholarship” (20/11/17 – 23/02/18), 
  3. “Bachelor of Biomedical Science (Honours) Research Thesis (26/02/18 – 01/11/18)”.

The contributors to the project are Andrea Soffe (“asof”), Dr Fabiana Kubke (“mfk”). There may also be input from Nazanin Ebrahimi (“naz”).

## Types of Data

Data will be gathered from chicken embryos (between stage 18-27), with various cranial nerve ganglia injected with fluorescent dye DiI. This will label those motor and sensory neurons in the hindbrain which make up the cranial nerve(s) injected. To ensure as much as possible that only neurons contained within the cranial nerve injected are labelled, checks for dye contamination will be carried out under a fluorescence microscope prior to incubation at 37°C.

The embryos will be inspected for the location of labelled neurons in the hindbrain. The embryos may be inspected as whole-mounts, or in cross section. If inspected in cross section, embryos will be embedded in HM solution gel and cut with a sliding microtome.

Embryos will be visualised with a fluorescence microscope (model: Leica M205 FA) connected to a PC. The microscope will also be used to capture the data in the form of images of the labelled neurons.

## Data Storage and Preservation

Physical samples will not be stored, except for those slides (on which slices of tissue have been mounted) which have been deemed relevant and useful to keep. These will be labelled as follows and stored in trays. The label for each slide should include:
  - Name of embryo (e.g. “asof001”)
  - The number of the 24 well tray into which the slices have been deposited between cutting and mounting  (e.g. “Tray 1”)
  - Individual tissue slice IDs (e.g. “A1-A6”) based off their position in the aforementioned 24 well tray.
  - The thickness of the slices on the slide (e.g. “70u”).

Slices will be mounted in a precise order with the slice first cut (usually most anterior) being in position 1 on Image 1. Slices will then be ordered as in Image 1, with position 6 holding the tissue slice cut last (usually most posterior). If there are less than 6 slices the same convention is followed as in Image 2, with position 5 holding the tissue slice cut last.

![Image](https://github.com/ansoffe/kubke.github.io/blob/master/assets/data/data-management-plan.png)

Electronic data will be stored on Github, within the repository “kubke.github.io” (URL: https://github.com/ansoffe/kubke.github.io). Images will be stored in the folder “_data”. Notes concerning each embryo will be stored in the folder “_posts”. Protocols will be stored in the folder “_protocols”. This information is also stored locally on asof’s PC, as a backup to prevent loss of data.

## Data Formats

The original images captured will be stored in Tagged Image File (.TIF) format. Reduced file size images will be stored in Portable Network Graphics (.PNG) format. Notes concerning each embryo, and protocols detailing how procedures were carried out, will be stored in Markdown (.MD) format.

Naming conventions will be as follows:

Image file names will contain:
  - The name of the embryo (e.g. “asof001”)
  - A number ID denoting which photograph of that particular embryo the file contains, preceded by an underscore (e.g. “_001”).
  - If the image is adjusted using image editing software, the file name must contain a number denoting which adjustment of the image this is, preceded by an underscore (e.g. “_01”).
  - For example, “asof001_001_01”

File names for notes concerning each embryo will contain:
  - The date the file was created, in the format YYYY-MM-DD (e.g. “2018-01-17”)
  - The name of the embryo, preceded by a dash (e.g. “-asof001”)
  - For example, “2018-01-17-asof001”

Protocol file names will contain:
  - The subject of the protocol, with each word separated by dashes (e.g. “hm-solution”)
  - The type of protocol, with each word separated by dashes (e.g. “recipe”)
  - For example, “hm-solution-recipe”

## Data Availability

The electronic data will be stored on the open access platform GitHub, meaning they are freely available to access. This platform also incorporates a version control system, so any changes to files are able to be viewed.