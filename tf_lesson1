from sklearn import tree
#weight in grams | smooth = 1, bumpy = 0
features = [[140, 1], [130, 1], [150, 0], [170, 0]]
# 0 = apple, 1 = orange
lables = [0, 0, 1, 1]
clf = tree.DecisionTreeClassifier()
clf = clf.fit(features, lables)

#input example - 170 grams, bumpy (0)
print clf.pedict([[170, 0]])
