products: id, title, description, price, image, availability, rating, vector(properties)
cart_products: id_cart, is_produs, cantitățe (constraint: >= 1)
cart: id_cart
review: scor, comentariu, user_asociat (fk: id_user)
user: id, nume, parola, mail, telefon etc
category: id_categorie, nume_categorie, description, 
