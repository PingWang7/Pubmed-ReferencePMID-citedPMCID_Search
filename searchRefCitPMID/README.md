**A tool to get the reference pmid and cited pmcid and cited pmid of the give PMID list.**

py function name： ‘searchRefCitPMID.py’

## install dependency
run <br>
`pip install -r requirements.txt`

## usage

#### firstly, switch the work directory to the py function directory.

one Example: <br>
`cd C:\Users\Username\Desktop\searchRefCitPMID` 

#### secondly, running the py function as the following form.

one Example: <br>
`Python searchRefCitPMID.py -i PMIDexample1.txt`

## the help document of the py function 'searchRefCitPMID.py' is as follows:

`Python searchRefCitPMID.py -h`


    Searching the reference PMID and cited PMCID,if necessary,change the cited PMCID to PMID
    
    output filenames                    : reference_cited_PMID_Result.txt
    PMCID-PMID converting INFO fileName : PMCID-PMID Converting Data.txt

    optional arguments :
      -h    --help    show this help message and exit
      -i    I         inputFile directory,"csv" or "txt" types.
      -coln INN       column name of pmid in inputFile,         default: pubmed_id
      -api  API       APIkey,                                   default: 3d20b15ed393b63857232da6279e8cd94708  , this API key may not be useful in the future.
      -t    T         tool,                                     default: my_tool
      -e    E         email,                                    default: my_email@example.com
      -cv   CV        weather convert the cited PMCID to PMID,  default: True   , if don't need, set 'False'.

## the output data are in the "Result" directory

"pmid to reference pmid.csv"

"pmid to cited pmcid.csv"

"pmid to cited pmid.csv"

"pmcid to pmid.csv"
