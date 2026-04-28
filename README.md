# CAI Technology — Smart-IoT Home Assistant Add-ons

Official Home Assistant add-on repository for CAI Technology's
**Smart-IoT** product line.

## Add this repository to your Home Assistant

1. Open **Settings → Add-ons → Add-on Store**.
2. Click the **⋮** menu (top right) → **Repositories**.
3. Add the URL:

   ```
   https://github.com/cai-technology/smart-iot
   ```

4. Refresh the store. The add-ons listed below will appear under
   **CAI Technology Smart-IoT Add-ons**.

## Add-ons in this repository

### CAI Bootstrap

Device onboarding agent for CAI-Hassio Smart-IoT systems.

- Enrols the device with the CAI Fleet control plane at
  `smart-iot.caitech.ro`.
- Maintains a persistent WebSocket tunnel for operator commands.
- Discovers IoT devices on the LAN (zeroconf, Solarman UDP) and
  auto-generates Lovelace cards for matched inverters.
- Exposes a sidebar panel **Pair Device** for the customer to link the
  device to their CAI-Auth account via RFC 8628 OAuth Device Flow.

See [`cai_bootstrap/`](cai_bootstrap/) for the manifest and source.

## Support

Issues and feature requests: https://github.com/cai-technology/smart-iot/issues

Commercial support: tehnic@caitech.ro

## Licence

Proprietary — © CAI Technology S.R.L. All rights reserved.
