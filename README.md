# GeneUP
I'm currently working on a tool to organize samples and arrange them into a CSV format for importing into GeneUP. As a biologist diving into programming for the first time at work, this Python program aims to create a user-friendly interface (GUI) for sorting Microbiology Samples according to their respective incubation times.

Currently, the program requires a time where incuation has already been entered into the sample data. However, I plan to introduce an incubation matrix in the future. This matrix will automatically determine when a sample has reached the required incubation time, based on the sample's media setting and placement in the incubator.

The sorting mechanism also accounts for test names or sample IDs. Upon selection, a second window displays how the samples are arranged on a 96-cell grid. This simulation mirrors the setup of the Biomerieux GeneUp PCR instrument's 96-well plate. Users can manually reorder samples by clicking a button and replacing it with a sample ID. I've prearranged the order in accordance with our lab's standard operating procedure (SOP). (*I also have an alternative version that sorts by the first test name, should that be preferred. Feel free to reach out for this.)

Once satisfied with the layout, simply click 'Save Layout' to generate a CSV file. This file can then be uploaded into the instrument and auto-plating, eliminating the need to manually enter sample IDs and selecting assay type, as well as eliminating manual worksheets. It also creates a record for quality control purposes.

Please note, the menu bar in this version is not configured. In future iterations, the program will also be integrated to work seamlessly with a SQL-based LIMS.

I'd greatly appreciate any comments or suggestions you might have.

