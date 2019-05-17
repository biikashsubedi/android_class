# Sucessfully Running or HomeWork
![fragmentexample2 gif](https://user-images.githubusercontent.com/23361796/55710104-9014d280-5a09-11e9-87d7-240e372342dc.gif)



# Answer these questions
#### Question 1
##### Which subclass of Fragment displays a vertical list of items that are managed by an adapter?

    ListFragment()

#### Question 2
##### Which of the following is the best sequence for adding a fragment to an activity that is already running?

    Declare the location for the fragment inside the activity's layout file using the <FrameLayout> view group, get an instance of the fragment and FragmentManager, and use the add() transaction.
    Declare the location for the fragment inside the activity's layout file using the <FrameLayout> view group. Then get an instance of the fragment and FragmentManager, begin a transaction, use the add() transaction, and commit the transaction.

#### Question 3
##### Which statement gets a reference to a fragment using the fragment's layout resource?
    SimpleFragment fragment = (SimpleFragment) fragmentManager.findFragmentById(R.id.fragment_container);
