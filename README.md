# taaabs-base-list
`<taaabs-base-list>` is a graphical componant that displays the list of all existing bases on one kTBS.
Then the user can select one of these bases.
An example, where `baseListId` is a string which contains the selected base, and `ktbsUrl` the URL of the kTBS:
    <taaabs-base-list id="baseList" 
                      ktbs-url="{{ktbsUrl}}"
                      base="{{baseListId}}">
    </taaabs-base-list>

