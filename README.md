products: id, title, description, price, image, availability, rating, vector(properties)\n
cart_products: id_cart, is_produs, cantitățe (constraint: >= 1)\n
cart: id_cart\n
review: scor, comentariu, user_asociat (fk: id_user)\n
user: id, nume, parola, mail, telefon etc\n
category: id_categorie, nume_categorie, description\n
