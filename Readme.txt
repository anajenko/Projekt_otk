Navodila za zagon kode

1. v kodi nastavi ustrezne poti do podatkov
2. za posamezno verzijo projekta zaženi pripradajočo python skripto/skripti (glej spodnjo shemo)


Verzija A: statistične značilke - mean, std, skewness

    a) randomForest ---> zaženi datoteko "mean,std,skewness_randomForest.py"

    b) SVM ---> zaženi datoteko "mean,std,skewness_randomForest.py" in potem še "mean,std,skewness_SVM.py"

Verija B: hog značilke

    ROTIRANA

        a) randomForest --> zaženi datoteko "hog_transposed_batch.py" in potem še "hog_model_randomForest.py"

        b) SVM --> zaženi datoteko "hog_transposed_batch.py" in potem še "hog_model_SVM.py"

    OBREZANA

        a) randomForest --> zaženi datoteko "hog_cropped_batch.py" in potem še "hog_model_randomForest.py"

        b) SVM --> zaženi datoteko "hog_cropped_batch.py" in potem še "hog_model_SVM.py"
