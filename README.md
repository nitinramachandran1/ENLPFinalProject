Our code is in the repository in 3 different files, each one corresponding to a separate model, outlined in our report



The data that our program uses can be found at the following github link:  https://github.com/spraakbanken/multiged-2023

Here, you can find the folders for each language containing annotated data. If you could download and save the files for each language under /My Drive/A4/GED/ that would align with our code. Below is how we created variables with the paths to where each data file is located. If you would like to change that path, you can edit this section of the code (copied and pasted here) so that it matches whatever path you have it saved in:

English_train_file = '/content/drive/My Drive/A4/GED/English/en_fce_train.tsv'
English_dev_file = '/content/drive/My Drive/A4/GED/English/en_fce_dev.tsv'
Czech_train_file = '/content/drive/My Drive/A4/GED/Czech/cs_geccc_train.tsv'
Czech_dev_file = '/content/drive/My Drive/A4/GED/Czech/cs_geccc_dev.tsv'
German_train_file = '/content/drive/My Drive/A4/GED/German/de_falko-merlin_train.tsv'
German_dev_file = '/content/drive/My Drive/A4/GED/German/de_falko-merlin_dev.tsv'
Italian_train_file = '/content/drive/My Drive/A4/GED/Italian/it_merlin_train.tsv'
Italian_dev_file = '/content/drive/My Drive/A4/GED/Italian/it_merlin_dev.tsv'
Swedish_train_file = '/content/drive/My Drive/A4/GED/Swedish/sv_swell_train.tsv'
Swedish_dev_file = '/content/drive/My Drive/A4/GED/Swedish/sv_swell_dev.tsv'

After that, our code is runnable by simply running each program!
