# Devide Subject and predicate in Vietnamese automatic
* using vncorenlp to split sentence and token in the sentence.
* use phonlp to find the pos-tag and dependecy parsing tree of sentence
* find the children which of the root in the sentence which has the depency tag is coordinate or punctutation and add it to a boundary_list
* split the clause arrcoding to to bound_list above
* call recursive to hand on every single clause at one time
