# ai_sismology
# **seisLM/**
  Travail effectué par Noam

  * **Fonctionnalités principales**

    * Inférence : prédiction de phases sismiques à l’aide de différents modèles.
    * Fine-tuning : adaptation des modèles sur des bases de données personnalisées (simulées ou non).
    * Conversion de données : traitement et conversion des archives `.zip` des données simulées de la base HEMEW-3D en formats exploitables (HDF5, CSV, etc.).
  * **Modèles supportés**

    * seisLM
    * PhaseNet
    * GDPick
    * EQTransformer

# **SeisMoLLM/**
  Travail effectué par Elias

  * **Fonctionnalités principales**
    * Conversion de données : traitement et conversion des archives `.zip` des données simulées de la base HEMEW-3D en formats exploitables (HDF5, CSV, etc.).
    * Modèles pré-entraînés : sur un chunk de la base de donnée STEAD ('dpk', 'baz', 'emg')
    * Inférence : prédiction à l’aide de différents modèles (phase picking, magnitude, back azimut).

  * **Modèles**

    * SeisMoLLM : (entraîné)
      * SeisMoLLM_dpk (phase picking)
      * SeisMoLLM_emg (estimation magnitude)
      * SeisMoLLM_baz (back-azimut)
    * seis_t : (non entraîné)
      * seis_t_dpk (phase picking)
      * seis_t_emg (estimation magnitude)
      * seis_t_baz (back-azimut)
