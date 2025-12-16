# ===== SIMULATION MODE (COLLEGE DEMO) =====
import random
import asyncio

async def simulated_start(user, wait_time, sem):
    async with sem:
        await asyncio.sleep(random.uniform(0.3, 0.9))
        print(f"🔧 {user} backend connected")

        await asyncio.sleep(random.uniform(0.2, 0.5))
        print(f"🎤 {user} mic active")

        print(f"⏳ {user} staying for {wait_time//60} minutes")
        await asyncio.sleep(wait_time)

        print(f"👋 {user} left after {wait_time//60} minutes")
